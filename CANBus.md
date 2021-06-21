# Canbus messages

From various sources on the internet, and from personal experimentation,
I have found the following CANBus messages:

```
0x201 (8 bytes)

0, 1:    RPM
2:       Unknown
3:       Unknown
4, 5:    Speed
6:       Unknown
7:       Unknown


0x420 (8 bytes)
0:       Oil Temperature
1, 2, 3: Something to do with odometer. Constantly increasing (could be distance?)
4:       Warning Lights. (D0 - Flash engine light, D1 - Solid engine light, D6 - Battery Light)
5:       Unknown
6:       Unknown
7:       Unknown
```