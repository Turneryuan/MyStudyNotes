# MyStudyNotes//我的程序员之路

  今天在写第一个hello world程序时遇到一个错误：

      Error: A JNI error has occurred, please check your installation and try again
      Exception in thread "main" java.lang.UnsupportedClassVersionError: HelloWorld has been compiled by a more recent version of the Java Runtime (class file version 58.0), this       version of the Java Runtime only recognizes class file versions up to 52.0
  
  这是因为我在安装jdk之前在官网上安装了java，导致了JRE与JDK版本不统一
  总结一下知识点：JDK工具包包含JRE，官网提供的JAVA安装包就是JRE，如果在其他电脑上需要运行JAVA程序不需要安装JDK，只需要安装JAVA(JRE)即可运行
