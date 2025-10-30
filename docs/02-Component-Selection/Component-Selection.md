---
title: Component Selection 
---




**Voltage Regulator**

1. NJM7805FA

   <img width="144" height="118" alt="image" src="https://github.com/user-attachments/assets/c0609540-c867-4b67-bb26-e6528d6dd6ac" />



   * $1.7
   * [Link to product](http://digikey.com/en/products/detail/nisshinbo-micro-devices-inc/NJM7805FA/805763)
  
    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Lightweight                                                       | Higher price |
    |                                                                   |Working temp lower (max- 85°C) |

2. LM7805T

   <img width="128" height="97" alt="image" src="https://github.com/user-attachments/assets/30cef9a5-1df8-4c35-be3c-9394cdece475" />

    

   * $0.33
   * [Link to product](https://www.digikey.com/en/products/detail/taejin/LM7805T/22237260)
  
    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | From the kit                                                      | Only sold in bulk ($33/100) |
    | Inexpensive                                                       |                      |

3. LM7805R

   <img width="132" height="96" alt="image" src="https://github.com/user-attachments/assets/45744c62-30cb-4aec-9836-b164c188a980" />


    
   * $0.33
   * [Link to product](https://www.digikey.com/en/products/detail/taejin/LM7805R/22237269)
  
    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Surface mount                                                     | Only sold in bulk ($266.66/800) |
    | Better  thermal conductivity                                      |                      |

**Choice:** Option 2: LM7805T

**Rationale:** This Volatge Regulator is part of the kit provided by the class and it fulfills our requirements hence, eliminating the need to order an external part.

**Motors**

1. M1N10FB11G 5V motor

     <img width="265" height="229" alt="Screenshot 2025-10-21 220238" src="https://github.com/user-attachments/assets/f51a6bd4-771a-4e88-a692-95ec44e6323e" />


    * $3.19/each
    * [link to product]((https://www.digikey.com/en/products/detail/nmb-technologies-corporation/M1N10FB11G/2417078))

    | Pros                                      | Cons                           |
    | ----------------------------------------- | ------------------------------ |
    | Inexpensive                               | Low torque                     |
    | Perfectly matches 5V rail                 | Tendency to spike in amperage when turned on |
    | Lightweight                               | Requires a diffrent Voltage regulator |
    | Available for bulk order for replacements |                                |
   
2. SE15K1BTYJ 12V motor
   
    <img width="152" height="111" alt="Screenshot 2025-10-21 220755" src="https://github.com/user-attachments/assets/200d5539-51be-4632-ba1e-df6a95210c7f" />


    * $9.24/each
    * [Link to product](https://www.digikey.com/en/products/detail/nmb-technologies-corporation/SE15K1BTYJ/6021448)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Higher Torque                                                     | Higher Price        |
    | Small and compact                                                 | Requires a diffrent Voltage regulator |

3. 2371 6V motor (Pololu)

   <img width="151" height="114" alt="image" src="https://github.com/user-attachments/assets/0165aa5f-2a6e-4fd3-abc3-cc830815b42e" />

   * $23.95
   * [Link to product](https://www.digikey.com/en/products/detail/pololu/2371/10450018?s=N4IgTCBcDa4MwHYCMACADgewDbYK4oBMBjFAWwwBcMAnEAXQF8g)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Highest Torque                                                    | Higher Price        |
    | Small and compact                                                 | Low RPM             |
    | Doesn't require an additional power rail                          |                     |
    | Lightweight                                                       |                     |
    
**Choice:** Option 3: 2371 6V motor (Pololu)

**Rationale:** This motor eliminates the need for an extra power rail, keeping the PCB design simple. It's lightweight and even though it costs higher than the alternatives it is well within our budget and eleminates the need to buy a voltage regulator other than the one provided in the kit, overall saving cost and increasing productivity.

**H-Bridge**

1. FAN8100N

   <img width="293" height="211" alt="image" src="https://github.com/user-attachments/assets/d553b5f5-8531-420e-9a78-519280cc6a4d" />


   * $1.16
   * [Link to product](https://www.digikey.com/en/products/detail/rochester-electronics-llc/FAN8100N/11558200)
  
    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | From the kit                                                      | Low working temp (75°C) |
    | Through hole                                                      |                     |

2. DRV8833PWPR

   <img width="142" height="123" alt="image" src="https://github.com/user-attachments/assets/ee1f9cd9-505e-4189-9fbe-2ab5cd513cb0" />


   * $2.6
   * [Link to product](https://www.digikey.com/en/products/detail/texas-instruments/DRV8833PWPR/2743167?s=N4IgTCBcDaICICUBqAOFBmdAFA6lhIAugL5A)
  
    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Built-in overcurrent and undervoltage protection                  | Higher price        |
    | Higher working temp (150°C)                                       |                     |
    | Surface mount                                                     |                     |

3. TB6615PG,8

   <img width="148" height="121" alt="image" src="https://github.com/user-attachments/assets/e58ff7cd-9e0a-4332-98a1-f083c1338bb6" />



   * $2.09
   * [Link to product](https://www.digikey.com/en/products/detail/toshiba-semiconductor-and-storage/tb6615pg-8/7809551)
  
    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Higher working temp (85°C)                                        | Package arrival too late |
    | Fewer pins                                                        |                     |
    | Through hole                                                      |                     |

**Choice:** Option 1: FAN8100N 

**Rationale:** This H-Bridge is part of the kit provided by the class and it fulfills our requirements hence, eliminating the need to order an external part. 


**Barrel Jack**

1. PJ-102AH
   
   <img width="148" height="146" alt="image" src="https://github.com/user-attachments/assets/711629bb-e7f1-4532-80e1-d3b02cca3b3b" />



   * $0.76
   * [Link to product](https://www.digikey.com/en/products/detail/cui-devices/PJ-102AH/408448)
  
    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | From the kit                                                      | Side load fragility |
    | Polybutylene Terephthalate for housing                            |                     |
    |                                                                   |                     |

2. PJ-202A
   
   <img width="151" height="151" alt="image" src="https://github.com/user-attachments/assets/bbb085f2-c910-4f62-8371-ee7f03e1c0d0" />



   * $0.7
   * [Link to product](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/pj-202a/252007)
  
    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Polybutylene Terephthalate for housing                            | Lower current rating |
    |                                                                   | Package arrival too late |

3. RAPC722X
   
   <img width="151" height="151" alt="image" src="https://github.com/user-attachments/assets/bbb085f2-c910-4f62-8371-ee7f03e1c0d0" />



   * $2.01
   * [Link to product](https://www.digikey.com/en/products/detail/switchcraft-inc/rapc722x/804747)
  
    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Better solder joint reliability                                   | Higher price |
    |                                                                   |Housing material specified as thermoplastic no specifications given |

**Choice:** Option 1: PJ-102AH

**Rationale:** This Barrel Jack is part of the kit provided by the class and it fulfills our requirements hence, eliminating the need to order an external part.



   
