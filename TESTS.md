# initialization test
## setup
Connected 
```mermaid
flowchart LR
  b004 --> b052 
  b052 --> r[100R between pinns 1 and 10 of J2]
  
```
## results
initialization works on a standard PoE switch.


# current test
## setup
Connected
```mermaid
flowchart LR
  b004 --> b052 
  b052 --> r[ariable resistor between pinns 1 and 10 of J2]
  
```
## results
| current | voltage | ripple |
|--|--|--|
|100mA|5V|250mA|
|500mA|4.9V|210mA|
|1A|4.8V|200mA|
|1.3A|4.8V|200mA|
