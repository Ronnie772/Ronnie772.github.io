---
title: CODE
---

## Overview
This is the code for microcontroller in the GARDEN BUDDY's motor subsystem.



 
    #include "mcc_generated_files/system/system.h"
    #include <xc.h>
    #include <stdint.h>


    #define FWD   LATBbits.LATB3   // FORWARDA
    #define REV   LATBbits.LATB0   // REVERSEA

    #define RF5_GetValue()  PORTFbits.RF5

    int main(void)
    {
    SYSTEM_Initialize();
    PWM1_16BIT_Enable();
    
    // ------------ LED on RC0 always ON ------------
    ANSELCbits.ANSELC0 = 0;   // Make RC0 a digital pin
    TRISCbits.TRISC0 = 0;     // RC0 = output
    LATCbits.LATC0 = 1;       // Turn LED ON permanently
    // ------------------------------------------------

    // Start with motor off
    FWD = 0;
    REV = 0;
    PWM1_16BIT_SetSlice1Output1DutyCycleRegister(0);
    PWM1_16BIT_LoadBufferRegisters();

    while(1)
    {
        uint8_t signal = RF5_GetValue();   // read the pin

        if (signal == 1)
        {
            // --------- FORWARD ---------
            REV = 0;
            FWD = 1;
            __delay_ms(1000);
        }
        else
        {
            // --------- REVERSE ---------
            FWD = 0;
            REV = 1;
            __delay_ms(1000);
        }

       
        PWM1_16BIT_SetSlice1Output1DutyCycleRegister(200);
        PWM1_16BIT_LoadBufferRegisters();

        __delay_ms(50);
        }
    }
   



