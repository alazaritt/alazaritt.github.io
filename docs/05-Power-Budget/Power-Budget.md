---
title: Power Budget
---

## Overview
This power budget confirms that the power supply and voltage regulator can safely provide enough current for all major components. By summing the estimated current draw of each component and taking into account a 25% safety margin, it ensures stable operation, prevents overload, and guides design decisions.

![budget1](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/05-Power-Budget/power%20budget%201.png?raw=true)
![budget2](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/05-Power-Budget/power%20budget%202.png?raw=true)

## Conclusions

From the prepared Power Budget, it is clear that the chosen power supply and voltage regulator meet the current and voltage requirements of all major components with a sufficient safety margin. It showns that the system will operate reliably without power issues.

The power budget was also used to determine the size of the fuse this system would require by identifying its maximum current draw. After listing every powered component and summing their worst-case maximum currents, a margin of error was added to account for possible surges and variability. The fuse rating was then selected to be above the maximum expected operating current so normal operation would not cause accidental blows, but still low enough to protect wiring and components during faults.

## Resouces

The power budget as an excel file is available [*here*](https://github.com/alazaritt/alazaritt.github.io/releases/download/powerbudget/PowerBudgetExample.xlsx).
