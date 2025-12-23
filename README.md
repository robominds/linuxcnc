
# MPG Pin Mapping:

|MPG Pin Name|MPG Wire Color|MPG DB25 Pin|Mesa 7i76u Pin Name|Mesa 7i76u Pin|Other|
|:------|:-----|:-----|:-----|:-----|:-----|
|Encoder +5v|Red|3|||PSU +5v|
|Encoder Gnd|Black|14|||PSU Gnd|
|Encoder A+|Green|16|MPG0A|TB5:1||
|Encoder A-|Purple|4|NC|||
|Encoder B+|White|17|MPG0B|TB5:2||
|Encoder B-|Purple/Black|5|NC|||
|||||||
|Field Pwr (+12v)|Orange/Black|1|||PSU +12v|
|X1|Grey|7|INPUT4|TB6:5||
|X10|Grey/Black|20|INPUT5|TB6:6||
|X100|Orange|8|INPUT6|TB6:7||
|Axis X Select|Yellow|21|INPUT7|TB6:7||
|Axis Y Select|Yellow/Black|9|INPUT8|TB6:8||
|Axis Z Select|Brown|22|INPUT9|TB6:9||
|Axis A Select|Brown/Black|10|INPUT10|TB6:10||
|Axis B Select|Pink|23|INPUT11|TB6:11||
|Axis C Select|Pink/Black|11|INPUT12|TB6:12||
|||||||
|LED +12v|White/Black|19|||PSU +12v|
|LED Gnd|Green/Black|12|||PSU Gnd|
|||||||
|E-Stop Field Pwr (+12v)|Blue|13|||PSU +12v|
|E-Stop|Blue/Black|25|INPUT12|TB6:13||


# Stepper Driver Mapping:

|Axis|Driver Pin|Mesa 7i76u Pin Name|Mesa 7i76u Pin|
|:-----|:-----|:-----|:-----|
|X Axis|Step -|STEP0-|TB2:2|
||Step +|STEP0+|TB2:3|
||Dir -|DIR0-|TB2:4|
||Dir +|DIR0+|TB2:5|
|||
|Y Axis|Step -|STEP1-|TB2:8|
||Step +|STEP1+|TB2:9|
||Dir -|DIR1-|TB2:10|
||Dir +|DIR1+|TB2:11|
|||
|Z Axis|Step -|STEP2-|TB2:14|
||Step +|STEP2+|TB2:15|
||Dir -|DIR2-|TB2:16|
||Dir +|DIR2+|TB2:17|

# Limit Switch Mapping

|Axis|Limit Type|Mesa 7i76u Pin Name|Mesa &i76u Pin|
|:-----|:-----|:-----|:-----|
|X Axis|Min/Home|INPUT4|TB6:5|
||Max|INPUT5|TB6:6|
|||||
|Y Axis|Min/Home|INPUT6|TB6:7|
||Max|INPUT7|TB6:8|
|||||
|Z Axis|Min|INPUT8|TB6:9|
||Max/Home|INPUT9|TB6:10|
|||||
