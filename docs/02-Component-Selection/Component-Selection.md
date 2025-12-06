---
title: Component Selection
---


*Table 1: Component selection (op-amp)*

**Op-amp**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/001/202/810/296%7E4040049%7EN%7E14_sml%28200x200%29.jpg)<br>Option 1.<br> Texas Instruments LM324N Op-Amp <br>$0.47/each<br>[link to product](https://www.digikey.com/en/products/detail/texas-instruments/LM324N/277627?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlgDuOhuCsO3lSPJC-xHYDZZ4&gclid=Cj0KCQjwjL3HBhCgARIsAPUg7a5X-zmEJKmNZMW9i0mgZEf2CLNNFkNgYv0SQP5R-WgAl9fvP6RbI8EaAvDtEALw_wcB)                 | \* Inexpensive<br>\* Low power <br>\* single supply operation                                               | \* No rail to rail input/output<br>\* Can't handle fast changing signals. |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/010/927/070/150%7EC04-005%7EP%2C-PD%7E14_sml.jpg)<br>\* Option 2. <br>\* MCP6004-I/P-ND Op-amp <br>\* $0.59/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlgDuOhuCsO3lSPJC-xHYDZZ4&gclid=Cj0KCQjwjL3HBhCgARIsAPUg7a5mU3gvabJ0blhmie9w81Q18eLWlkL3ABVWDsQnz9WJitiZg9sx0lcaAsvLEALw_wcB) | \* Integrated amplifier <br>\* Wide operating voltage <br> \* compact design | * Potential power noise <br>\* Sensitivity limitations <br>\* Limited frequency range                                                        |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/200/086/208/505%7ER-14%7ER%2CS%7E14_sml.jpg)<br>\* Option 3. <br>\* AD8669ARZ Op-amp <br>\* $9.36/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/analog-devices-inc/AD8669ARZ/1766867?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlgDuOhuCsO3lSPJC-xHYDZZ4&gclid=Cj0KCQjwjL3HBhCgARIsAPUg7a6_oGgJXxEZETfUrJQS6UQywQOC_dS5omczopwZEbmNXHzO9C1Lu8saAvGqEALw_wcB) | \* Dual op-amp <br>\* Rail to rail input/output <br> \* Low offset | * More expensive <br>\* Dual op-amp may limit ideas                                                        |

**Choice:** Option 2: MCP6004-I/P-ND Op-amp

**Rationale:** This op-amp will be most ideal to work with since it balances low power, high signal range, compact size, and cost. Unlike the other options, it handles faster signals, and it is more affordable and simpler than them. It meets our low-power, space-constrained audio amplification requirements.



*Table 1: Component selection (microphone)*

**Microphone**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://res.cloudinary.com/rsc/image/upload/b_rgb:FFFFFF,c_pad,dpr_1.0,f_auto,q_auto,w_700/c_pad,w_700/F7542100-01)<br>Option 1.<br> RS PRO 7542100 Microphone <br>$0.61/each<br>[link to product](https://us.rs-online.com/product/rs-pro/7542100/71815654/?gclsrc=aw.ds&gad_source=1&gad_campaignid=22593105799&gbraid=0AAAAAD-9z7Fd9Zc_kUm8eCjX4V2buscHA&gclid=EAIaIQobChMIm4HlmtyGkAMVwTlECB1H-ABrEAQYASABEgLx1_D_BwE)                 | \* Wide frequency response<br>\* High signal to noise ratio <br>\* Omni directoinal sound detection                                             | \* Limited output constraints<br>\* Can't handle extreme temps. |
| ![](https://www.sparkfun.com/media/catalog/product/cache/a793f13fd3d678cea13d28206895ba0c/1/2/12758-02.jpg)<br>\* Option 2. <br>\* Sparkfun microphone breakout <br>\* $8.50/each <br>\* [Link to product](https://www.sparkfun.com/sparkfun-electret-microphone-breakout.html) | \* Integrated amplifier <br>\* More compact <br> \* Wide operating voltage | * More expensive <br>\* Limited frequency range <br>\* Potential power noise                                                       |           
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/2/001/212/MFG_MFG_CMA-4544PF-W%28640x640%29.jpg?hidebanner=true)<br>\* Option 3. <br>\* CMA-4544PF-W Microphone <br>\* $0.76/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices-/CMA-4544PF-W/1869981?gclsrc=aw.ds&gad_source=1&gad_campaignid=20243136172&gbraid=0AAAAADrbLlj1J1-wrnvGXGv0h4K-eIZg2&gclid=Cj0KCQjwjL3HBhCgARIsAPUg7a68c1BZp6LEFrLCHPUIop5vsIPro80buftPfndr3yCjhH8FneqTxqMaAmJ3EALw_wcB) | \* Minimizes background noise <br>\* Wide frequency range t <br> \* Uniform sensitivity in all directions | * Weaker sensitivity at lower voltages <br>\* requires external tuning <br>\* Lower sensitivity                                                      |

**Choice:** Option 3: CMA-4544PF-W Microphone 

**Rationale:** The compact size of this microphone will allow it to easily fit within the device. It's wide frequency range, omni-directional noise detection, and high signal-to-noise ratio lets it precisely read sound levels while minimizing background noise. 


*Table 3: Component selection (voltage regulator)*

**Voltage regulator**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/300/702/797/296%7E4204749%7EKCS%7E3_sml.jpg)<br>\*Option 1.<br>\* Texas Instruments UA7805CKCSE3 voltage regulator<br>\* $1.43/each<br>[link to product](https://www.digikey.com/en/products/detail/texas-instruments/UA7805CKCSE3/1494012?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlgDuOhuCsO3lSPJC-xHYDZZ4&gclid=CjwKCAjwr8LHBhBKEiwAy47uUj_aABNZfAHrrfIFFVugA2kvcGc2_yKuF62wHTeIrLmOseNHn_papxoCxrEQAvD_BwE)                 | \* Built in circuit protection<br>\* Fixed linear regulator <br>\* can tolerate high input voltages                                               | \* May overheat quickly<br>\* High dropout <br>\* May shut entire system if overheated |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/003/210/775/1662%7EYS003-D-P-SD-2.0%7EY%7E3_sml%28200x200%29.jpg)<br>\* Option 2. <br>\ S-812C50AY-B2-U voltage regulator <br>\ $2.28/each <br>\ [Link to product](https://www.digikey.com/en/products/detail/ablic-inc/S-812C50AY-B2-U/3609196?gclsrc=aw.ds&gad_source=1&gad_campaignid=21162233706&gbraid=0AAAAADrbLliUjMZmW9Noe5ejE0zIGhnDP&gclid=CjwKCAjwr8LHBhBKEiwAy47uUvWiQhtwIGzL-1CnmucFMm5j1DfwWEFBi4mdaTywGiV6SN9JvQ3suxoCgcwQAvD_BwE) | \* Low current draw <br>\* Low dropout <br> \* More compact | * Limited output current <br>\* may not be compatible with all low voltage systems                                                         |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/300/415/110/497%7ETO220-3TO220AB%7E%7E3_sml.jpg)<br>\* Option 3. <br>\* L7805CV voltage regulator <br>\* $0.50/each <br>\ [Link to product](https://www.digikey.com/en/products/detail/stmicroelectronics/L7805CV/585964?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlgDuOhuCsO3lSPJC-xHYDZZ4&gclid=CjwKCAjwr8LHBhBKEiwAy47uUvEnyl-yuok7hRfbfTtKdwOWhlaiNQILElJN_30pZdMZOOKc8hjwuxoCNd0QAvD_BwE) | \* High output current <br>\* Built in thermal and circuit protection <br>\* Inexpensive | * High dropout <br>\* Efficiency decreases with higher voltage                                                       |

**Choice:** Option 3: L7805CV voltage regulator

**Rationale:** This one is ideal, as it offers a fixed 5 V output with up to ~1.5 A of current, built‑in protection, and ease of use with minimal external components. Its reliability and tolerance to voltage variations make it a safe, straightforward choice as there’s enough headroom voltage to dissipate heat.


*Table 4: Component selection (button/switch)*

**External Power Supply**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/300/083/564/WR9HD1333CCP-F%28R6B%29_sml.jpg)<br>Option 1.<br> WR9HD1333CCP-F(R6B) (V Power Supply <br>$0.83/each<br>[link to product](http://digikey.com/en/products/detail/globtek-inc/WR9HD1333CCP-F(R6B)/13245472?gclsrc=aw.ds&gad_source=1&gad_campaignid=20232005509&gbraid=0AAAAADrbLliAWNAe3kc2ZQhIbakXEpBWA&gclid=CjwKCAiAxc_JBhA2EiwAFVs7XDCIccQXBKXO9Xae1sWETsOyjtnmOLRt1nxLLyYAz2bQOsTiH3w7hhoCo0AQAvD_BwE)                 | \* Wide input voltage range<br>\* Sufficient voltage for small circuits <br>\* Operates efficiently and consistently                                               | \* Fixed barrel plug and polarity may limit compatibility <br>\* May have operating temperature restrictions |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/008/949/MFG_DCU120050D4740_sml%28200x200%29.jpg)<br>\* Option 2. <br>\* DCU120050D4740 12V power supply <br>\* $0.10/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/jameco-reliapro/DCU120050D4740/25966493?gclsrc=aw.ds&gad_source=1&gad_campaignid=20232005509&gbraid=0AAAAADrbLliAWNAe3kc2ZQhIbakXEpBWA&gclid=CjwKCAiAxc_JBhA2EiwAFVs7XMIr1HiwdeUjFCkA2YSm7CzZHr0R3VAAe2WT0fHnovfo6hBdBaTLCRoCLroQAvD_BwE) | \* More compact design <br>\* Constant voltage supply <br> \* Low cost | * Unregulated current output <br>\* Low output current              |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/002/492/MFG_418117270901_sml%20%28200x200%29.jpg)<br>\* Option 3. <br>\* BestCH 9V 3.0A AC Adapter <br>\* $0.85/each <br>\ [Link to product](https://www.amazon.com/gp/product/B09ZTKTLGW/) | \* Stable and reliable output <br>\* Automatic overload cut off <br> \* No voltage fluctuations at power on | * Higher heat output <br>\* Cant handle high voltage                                                      |

**Choice:** Option 3: BestCH 9V 3.0A AC Adapter

**Rationale:** This power supply offers a clean, stable output with built-in overload protection, making it safer for sensitive electronics. Its smooth power-on behavior helps prevent voltage spikes that can damage circuits or cause unpredictable startup issues. Overall, it provides a good balance of reliability, protection features, and convenience. 

**Overall Rationale:** Each component was chosen through an evaluation of performance, cost, and compatibility with the system’s low-power and compact design requirements. The MCP6004-I/P op-amp was chosen for its low power consumption, high signal range, and stable signal amplification. This makes it ideal for accurate signal processing while keeping cost and complexity low. The CMA-4544PF-W microphone provides a wide frequency range and high signal-to-noise ratio, ensuring clear and reliable sound detection while remaining compact enough to fulfill project requirements.

To maintain stable operation, the L7805CV voltage regulator was selected for its reliable 5 V output, built-in protection features, and simplicity, making it optimal for low-power circuitry. Finally, the BestCH 9V 3.0A AC Adapter provides a safe and stable option for powering the board, offering built in protections against voltage spikes as well as regualted voltage outputs for the circuit


*Table 4: Final Components Selected (summary)*

| **Part Name/Description** | **Manufacturer/Part Number** | **Function** | **Rationale** |
|:--------------------|:----|:---------------|:-----|
Op-amp | Microchip/MCP6004-I/P-ND | Amplifies and conditions analog signal from the microphone | This op-amp balances low power and high signal range regardless of signal speed | 
Microphone | Same Sky/CMA-4544PF-W | converts sound to an electrical signal | It provides a wide range frequency response and stable sensitivity. Its small size, low power requirement, and standard interface also simplify integration within the subsytem | 
Voltage regulator |STMicroelectronics/L7805CV  | To ensure that only 5V of power runs through the circuit | It allows for a fixed 5 V output with up to ~1.5 A of current. Its reliability and tolerance to voltage variations ensure safety, as there’s enough headroom voltage to dissipate heat. |

PowerSupply | BestCH/EA10302 | Provides 9V and 3A of power to the circuit | It integrates lots of safety features to protect the circuit, ensuring that the correct amount of voltage and current runs through it at all times.|



*Table 5: MCC Pinout*

| **Component** | **Pin** | **Pin Type** | **Direction** | **Purpose** |
|:--------------------|:----|:---------------|:-----|:-----|
Microphone (ADC) | RA0 | Analog | Input | Signal from microphone is read and analyzed by microcontroller |
Ribbon connector  | RA1 | Digital | Output | Sends the received signal from the micrphone to a teammate's board via a ribbon connector |
Button | RB4 | Digital | Input | Provides a manual override button if a user wants to trigger the light regardless of soud detction |
LED | RF3 | Digital | Output | Turns on when a signal is sent to the other board |
