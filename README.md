
# MPG Pin Mapping:

|MPG Pin Name|MPG Wire Color|MPG DB25 Pin|DB25 to Mesa Color|Mesa 7i76u Pin Name|Mesa 7i76u Pin|Other|
|:------|:-----|:-----|:-----|:-----|:-----|:-----|
|Encoder +5v|Red|3||||PSU +5v|
|Encoder Gnd|Black|14||||PSU Gnd|
|Encoder A+|Green|16|Orange/White|MPG0A|TB5:1||
|Encoder A-|Purple|4||NC|||
|Encoder B+|White|17|Green/White|MPG0B|TB5:2||
|Encoder B-|Purple/Black|5||NC|||
|||||||
|Field Pwr (+12v)|Orange/Black|1||||PSU +12v|
|X1|Grey|7|Blue|INPUT10|TB6:11||
|X10|Grey/Black|20|Red/Black|INPUT11|TB6:12||
|X100|Orange|8|Purple|INPUT12|TB6:13||
|Axis X Select|Yellow|21|Orange/Black|INPUT7|TB6:8||
|Axis Y Select|Yellow/Black|9|Grey|INPUT8|TB6:9||
|Axis Z Select|Brown|22|Yellow/Black|INPUT9|TB6:10||
|Axis A Select|Brown/Black|10|White|INPUT4|TB6:5||
|Axis B Select|Pink|23|Green/Black|INPUT5|TB6:6||
|Axis C Select|Pink/Black|11|Pink|INPUT6|TB6:7||
|||||||
|LED +12v|White/Black|19||||PSU +12v|
|LED Gnd|Green/Black|12||||PSU Gnd|
|||||||
|E-Stop Field Pwr (+12v)|Blue|13||||PSU +12v|
|E-Stop|Blue/Black|25|Pink/Black|INPUT13|TB6:14||
  
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

|Axis|Limit Type|Mesa 7i76u Pin Name|Mesa 7i76u Pin|
|:-----|:-----|:-----|:-----|
|X Axis|Min/Home|INPUT20|TB5:5|
||Max|INPUT21|TB5:6|
|||||
|Y Axis|Min/Home|INPUT22|TB5:7|
||Max|INPUT23|TB5:8|
|||||
|Z Axis|Min|INPUT248|TB5:9|
||Max/Home|INPUT25|TB5:10|
|||||

# Other Mesa 7i76u Mappings
|Function|Mesa 7i7u Pin Name|Mesa 7i76u Pin|
|:-----|:-----|:-----|
|E-Stop|Input14|TB6:15|

![Internal MPG DB25 Pinout](https://github.com/robominds/linuxcnc/blob/cef37ab60e2effe825a4e657c1aadf4b89c3387f/images/Juxinice%20DB25%20Cable%20pinout.png 'CNC Controller Internal MPG Pendant DB25 Pinout')
