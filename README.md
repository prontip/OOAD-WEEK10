

พรทิพย์  เกิดรัตน์  57030199

# OOAD-WEEK10
รูปที่1

 ```
 @startuml
title XeroxPaper
user -> button : Press(on)
button -> machine: SendCommandOn()
user -> AreaForPutPaper :PutPaper
user -> button : Press(Xerox)
button -> machine: SendCommandXerox()
machine -> MachineScan : SendCommandScan
MachineScan -> machine : informationScan
machine -> Printer : SendCommandPrinter
@endum
```

![](http://www.plantuml.com/plantuml/img/XOun3i8m34Ntd29ZEt213gW8YGqHgGkhQOs8r3Z8SIIEJn82P45irl_Fpnw304jqgn8hA-epidyOk2Eh693rPgilKSIJ7hHX3A7prAiQfTB1VBE4WvwGbhrt3cWvKTT_jdUCSF1ieXIh7jxJBt_vuD-90gKhjSlOyJLECsHNm-P4jUtNcK1BLyyEn7egO6CqR4doowsjXcfCKNHAFG40)


รูปที่2

 ```
@startuml
Title SentmassageOnLine
user -> button : Press()
button -> machine: SendComSunGOn()
machine -> displayScreen: SendComSunGOn()
user -> displayScreen: PutPassword()
displayScreen -> machine: (PasswordWrong)remind
machine -> displayScreen: (PasswordWrong)SendMessageRemind
displayScreen -> machine: (PasswordTrue)dumnenkantoe
machine -> displayScreen: (PasswordWrong)ShoeHomeMobile
machine -> displayScreen: pressAppLine
displayScreen -> machine: openappLine
machine -> displayScreen: showHomeline
machine -> displayScreen: pressSelectChat
displayScreen -> machine: CommandOpenChat
machine -> displayScreen: ShowChat
machine -> displayScreen: PimMassge
machine -> displayScreen: PressSentMassge
displayScreen -> machine: commandSentChat
machine -> linefriend: sentMessage
@endum
 ```
 
 ![](http://www.plantuml.com/plantuml/img/bP4nRiCm34Ltdy9ZFFG26OeK6TgXXeKwG6R5OcsX4cL858BSlfJj375XjLt5HxrFyX18UehM52TD1ieMaAmCGVRGuBj6A680NpuzbvT8vB3Sby932BkgM1wuP6KtCBfFtUheR1lnjK56ba9Yb0wZaRUsym3uaxnRLfY893ZDrNd5q4FnGRoxKsVliAyyM8qger_nAKqDqzGVS-iVL2SVeLBH8k2NH7Bm3z_WuCrPgDr5crpVc7RzCexJ9ROpkH5GBjJsPs5mrsGrUMnojc2We-CWAQFb0rg9gc7xH6REpUfV4A5jpKlgSz7470rf8RUZTNEqnAwzQVnFh_dal9Bqrtpuui0lqHRV)



รูปที่3


 ```
@startuml
title PlusOnCalculator
user -> button : Press(on)
button -> machine: SendCommandOn()
machine -> displayScreen: ShowlekZeo()
user -> button : Press(Multiplicand)
button -> machine: SendCommandMultiplicand()
machine -> displayScreen: ShowlMultiplicand()
user -> button : Press(symbolpush)
button -> machine: SendCommandpush()
machine -> displayScreen: Showsymbolpush()
user -> button : Press(toorboog)
button -> machine: SendCommandtoorboog()
machine -> displayScreen: ShowToorBoog()\
user -> button : Press(symbolequal)
button -> machine: SendCommanequal()
machine -> displayScreen: ShowSum()
@endum

 ```
 
 ![](http://www.plantuml.com/plantuml/img/XS-n2i8m483XFK-HKGTVe8CKdSL2dSGbRGyRlEHgSeVqxOsbeWWr6NDVxYUgZ6m2YqF5bX5qXHAFVc-m5JHCGKc4e3TRtGWpULteAa2CA_9hDL-beJDjRpqKkWRVxSavuxkZNwtLF7YPpiO1pLYt0S0dsTC3uNO6IcmXSX1aEw1jqxfSxjlcmpzweHz7rn0E4ljS_MMorS-wvIGJXORecWk-NJPwId0tmSl_Ry9T36QoayacQt79bEcLE9NE4m00)



รูปที่4


 ```
@startuml
title SpinFruit
user -> button : Press(on)
button -> machine: SendCommandOn()
user -> GlassJar : PutFruitInGlassJar 
user -> button : Press(spin)
button -> machine: SendCommandspin()
machine -> motor: spin()
user -> button : Press(stop)
button -> machine: SendCommandstop()
machine -> motor: stop()
@endum
 ```
 
 
![](http://www.plantuml.com/plantuml/img/XOvD2i8m48NtESKisuKNw48AWg8RXPuWse21PARCp_sRrj2LfTlvtllUzAAUrN9o6ZK56AQ8LxQepYGmdCxmDbL2wE35GQGXR5qz5PZzvninT30472-KiyVnYKsxjM_9YpmyBttJrNp7xRWt8kMBevabKuOgMbEan1rKiATMcWxL9VDV_GDzYLfsCm00)


รูปที่5


 ```
@startuml
title Washing machine
user -> HoleForPutCoin : PutCoin 
HoleForPutCoin -> machine:SendCountCoin()
machine -> displayScreen: ShowCountCoin()
user -> HoleForPutCoin : PutFuullCountCoin 
HoleForPutCoin -> machine:SendFuullCountCoin()
machine -> WashingMachine: WashingmachineWork()
@endum
```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuIh9BCb9LGXFBCx8p4jNo4rC1jAfNAN5gKKAkdOA7lavgMxvHG6b9SxvcNaALWem5XUQ350jLAzLS6fUYdD-QHvOGaEJ2oeEKfAIMLoGarWPd5oKcffdfH2SaL-Eh1AVhMwbfJavSCM4x4TLZUe8g5zzeSfXVAYAyFoYRA1w1w0XfRbS0000)


Sequence Diagram


README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 
