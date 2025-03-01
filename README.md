# IALRSP_dataset
# Integrated Assembly Line Reconfiguration and Scheduling Problem Dataset

## Fileformat

Integrated assembly line reconfiguration and scheduling problem dataset is composed of one file in ".txt" file format.

“New Product Data-PPGraph_Operation” describes the relevant information of all the alternative resources for an operation.
The information in each line is as follows：
```yaml
<number of operation> <name of first resource>(process time in `s`) <name of second resource>(process time in `s`)……
```

“New Product Data-PPGraph_Precedence” describes the relevant information of the operation precedence.That represents a process precedence, indicating that the first operation is better than the second operation.
The information in each line is as follows：
```yaml
<first operation> <second operation>.
```

“New Product Data-Monthly Production” describes the monthly production of each product.
The information in each line is as follows：
```yaml
<case num> <name of first product>(its monthly production),<name of second product>(its monthly production) ……
```

## License

This work is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license.

```yaml
SPDX-License-Identifier: CC-BY-4.0
```
