jdtools(jar or dex tools)(由于工作原因，停止更新)
=======

Toolkit for confuse the .class or .dex files, making it difficult to read for cracker, and so on...

jdtools contains two compment

- [merger](https://github.com/noverguo/jdtools/tree/master/merger) is a tool to combine multiple methods into one, so that to ease restrictions android 65k method of quantity, and increasing the difficulty of analysis.    
- [jc](https://github.com/noverguo/jdtools/tree/master/merger) is a tool for confuse the jar or dex. it contain some feature, such like reflect, refactor, merge(use the merger compment), jni and so on. this tool will added in subsequent.

this tools has used some lib:
  - [asm](http://asm.ow2.org/) lib to edit the bytecode. 
  - [gson](http://code.google.com/p/google-gson/) lib to operate json.
  - [dex2jar](http://code.google.com/p/dex2jar/) tools to assembly jar to dex or disassembling dex to jar.


=======
一个用于操作.class或.dex文件的工具集，让破解的人更加难以阅读等等，请留意后续更新。

jdtools包含了2个组件

- [merger](https://github.com/noverguo/jdtools/tree/master/merger) 是一个把多个方法合并成一个的工具，因而可以用来缓解adnroid dex方法数量的65K(65536)的限制，同时可以加大分析的难度。
- [jc](https://github.com/noverguo/jdtools/tree/jc) 是一个用来混淆jar或dex的工具。它包含了多个特性，如反射、重构、合并（使用merger组件）、jni等等。 此工具会在后续更新。


这个工具用了一些库：
  - [asm](http://asm.ow2.org/) 一个操作bytecode的库
  - [gson](http://code.google.com/p/google-gson/) 一个操作json的库
  - [dex2jar](http://code.google.com/p/dex2jar/) 一个用于jar和dex之前相互转换的工具


