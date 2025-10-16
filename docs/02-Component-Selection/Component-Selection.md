---
title: Component Selection Example
---

## Examples

### Style 1


*Table 1: Component selection*

**Op-amp**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/001/202/810/296%7E4040049%7EN%7E14_sml%28200x200%29.jpg)<br>Option 1.<br> Texas Instruments LM324N Op-Amp <br>$0.47/each<br>[link to product](https://www.digikey.com/en/products/detail/texas-instruments/LM324N/277627?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlgDuOhuCsO3lSPJC-xHYDZZ4&gclid=Cj0KCQjwjL3HBhCgARIsAPUg7a5X-zmEJKmNZMW9i0mgZEf2CLNNFkNgYv0SQP5R-WgAl9fvP6RbI8EaAvDtEALw_wcB)                 | \* Inexpensive<br>\* Low power <br>\* single supply operation                                               | \* No rail to rail input/output<br>\* Can't handle fast changing signals. |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/010/927/070/150%7EC04-005%7EP%2C-PD%7E14_sml.jpg)<br>\* Option 2. <br>\* MCP6004-I/P-ND Op-amp <br>\* $0.59/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlgDuOhuCsO3lSPJC-xHYDZZ4&gclid=Cj0KCQjwjL3HBhCgARIsAPUg7a5mU3gvabJ0blhmie9w81Q18eLWlkL3ABVWDsQnz9WJitiZg9sx0lcaAsvLEALw_wcB) | \* Quad op-amp <br>\* Low current draw <br> \* rail to rail | * More noise <br>\* Lower gain bandwidth                                                         |
| ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/200/086/208/505%7ER-14%7ER%2CS%7E14_sml.jpg)<br>\* Option 2. <br>\* AD8669ARZ Op-amp <br>\* $9.36/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/analog-devices-inc/AD8669ARZ/1766867?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlgDuOhuCsO3lSPJC-xHYDZZ4&gclid=Cj0KCQjwjL3HBhCgARIsAPUg7a6_oGgJXxEZETfUrJQS6UQywQOC_dS5omczopwZEbmNXHzO9C1Lu8saAvGqEALw_wcB) | \* Dual op-amp <br>\* Rail to rail input/output <br> \* Low offset | * More expensive <br>\* Dual op-amp may limit ideas                                                        |

**Choice:** Option 2: MCP6004-I/P-ND Op-amp

**Rationale:** This op-amp will be most ideal to work with due to its high signal range and low power operation. It has a compact design which will reduce board space, and it is also extremly cost-efficient.

### Style 2

> Also acceptable, more markdown friendly

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](image1.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
