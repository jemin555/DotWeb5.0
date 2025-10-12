📘 DotWeb5 Tutorial
Unit 1: Introduction to the DotWeb5 Programming Language

🔍 Definition
DotWeb5 is a programming language designed for:
- Code security
- Console-based applications
- Learnability and simplicity
- Advanced software development
- Remote X applications
- Web applications
- Machine learning
It is symbolized by a star icon and is used with frameworks like Scroll Framework within the DotWeb5 ecosystem.

🧠 About DotWeb5
DotWeb5 was invented by Wilmix Jemin J in 2013, evolving from Java and DOTWEB3.0. Earlier versions of Java (JDK 1.7 and JDK 1.8) were vulnerable to source code extraction using tools like JAD decompiler.
We are grateful to our friends, including Venkat, GitHub, and many others, for their support in this journey.


⚠️ Limitations of Java and C#
- Java .class files are easily decompiled using tools like JAD.
- This makes Java less secure for compiler development.
- DotWeb5 was created to overcome these limitations and is ideal for building data structures and compilers.
- It accepts .java7 files and translates them into DotWeb5 class files, which are incomprehensible to hackers.
- DotWeb5 is not focused on GUI development (e.g., Java Swing).

❓ Can You Build a Compiler Like Java?
Yes. You can use Java to build a Java-like compiler or any other compiler. While some may criticize this approach, it is valid according to the principles of compiler design.
The same logic applies to building compilers for C or other languages.
However, I personally avoid GUI frameworks like Java Swing or J2EE due to misinformation spread by competitors or malicious actors, which could harm my products.


🛠️ My Compiler Design Journey
- At age 21, I built a compiler using VC++.
- Later, I developed a mini compiler in Java.

🚀 Why DotWeb5 Is More Advanced Than Other Languages
- DotWeb5 and Java/J2EE are both fluent and expressive, like natural English.
- DotWeb5 helps reduce lines of code, improving productivity.
- Both follow camelCase conventions and integrate beautifully with IDEs like IntelliJ IDEA.
- The creator of DotWeb5 is not interested in robotics, as it may replace human roles.
- We support AI, but not robots.




📘 DotWeb5 Programming Modules
DotWeb5 is divided into two modules:
- DotWeb5 – Module 1
- DotWeb5 – Module 2

🔍 About DotWeb5 Modules
DotWeb5 keywords are designed to resemble those in Java, making it easy for Java professionals and companies to learn and adopt. While most syntax is familiar, DotWeb5 introduces several attractive and unique constructs.
DotWeb5 is used in:
- Console applications
- Web applications
- Machine learning
- Data science
- Remote X applications
Module 1 is primarily used by Java and DotWeb5 professionals. The Remote X Application module will be released after the machine learning and data science modules are finalized.

🔐 DotWeb5 Reserved Keywords – Module 1
DotWeb5 includes a set of reserved keywords that cannot be used as variable names, method names, class names, or other identifiers.
✅ Keyword Overview
|  |  | 
| <JAVA7> |  | 
| </JAVA7> |  | 
| abstract |  | 
| assert |  | 
| boolean | truefalse | 
| break |  | 
| byte |  | 
| case |  | 
| <CATCH> | <TRY> | 
| char |  | 
| <CLASS> |  | 
| continue |  | 
| default |  | 
| do | while | 
| double |  | 
| else |  | 
| enum |  | 
| <--- |  | 
| final |  | 
| <FINALLY> |  | 
| float |  | 
| for |  | 
| if |  | 
| --> |  | 
| <IMPORT> |  | 
| instanceof |  | 
| int |  | 
| interface |  | 
| long |  | 
| native |  | 
| new |  | 
| <PACKAGE> |  | 
| private |  | 
| protected |  | 
| public |  | 
| return |  | 
| short |  | 
| <SHARED> |  | 
| <SUPER> |  | 
| switch |  | 
| synchronized |  | 
| <IS> |  | 
| throw |  | 
| throws |  | 
| transient |  | 
| <TRY> |  | 
| void |  | 
| volatile |  | 
| while |  | 



🧪 Sample Program: testme.java7
<JAVA7>

public <CLASS> testme 
//--> Runnable
<--- <Thread>

<%

public <SHARED> int sum() {
  int b;
  return (2 + 3);
}

public synchronized void <RUN> {
  <TRY> {
    <PRINTLINE>("Under Weight is less than 15. Your health is worst = " + sum());
    <Thread>.sleep(1000);
    throw new Exception();
  }

  <CATCH> (Exception e) {
    <PRINTLINE>("" + e);
  }
}

<MAIN>
<%
<TRY> {
  testme t <NEW> testme();
  t.start();

  testme t1 <NEW> testme();
  t1.start();

  int value = 15;
  if (value >= 15) {
    assert value >= 25 : "Underweight";
    <PRINTLINE>("Value is " + value);
  } else {
    <PRINTLINE>("Under Weight is less than 15");
  }
}

<CATCH> (Exception e) {
  <PRINTLINE>("" + e);
}

<FINALLY> {
  <PRINTLINE>("Note: Please enter accurately");
}
%>

</JAVA7>



🖥️ Output
Value is 15
Under Weight is less than 15. Your health is worst = 5
Under Weight is less than 15. Your health is worst = 5
Note: Please enter accurately
java.lang.Exception
java.lang.Exception




