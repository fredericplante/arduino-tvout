# arduino-tvout
from code.google.com/p/arduino-tvout��

**Connections**

<img src="http://farm5.static.flickr.com/4087/5225072558_5f5f760037.jpg" width="50%"/>

YNC is on OCR1A and AUDIO is on OC2A 

--------------------------------------------
| MCU               | SYNC | VIDEO | AUDIO |
--------------------------------------------
|m168,m328          |  B1  |  D7   |  B3   |
|NG,Decimila,UNO    |   9  |   7   |  11   |
|m1280,m2560        |  B5  |  A7   |  B4   |
|Mega               |  11  |A7(D29)|  10   |
|m644,m1284p        |  D5  |  A7   |  D7   |
|sanguino           |  13  |A7(D24)|   8   |
|AT90USB1286        |  B5  |  F7   |  B4   |
--------------------------------------------


There are some timing issues with the m1284p, may be related to sanguino core.
