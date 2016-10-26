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
 
