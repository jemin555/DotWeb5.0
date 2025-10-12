📘 DotWeb5 Tutorial
====================


Unit 1: Introduction to the DotWeb5 Programming Language
=======================================================


🔍 Definition
===============


DotWeb5 is a programming language designed for:
- Code security
- Console-based applications
- Learnability and simplicity
- Advanced software development
- Remote X applications
- Web applications
- Machine learning
It is symbolized by a ⭐ star icon and is used with frameworks like Scroll Framework within the DotWeb5 ecosystem.

🧠 About DotWeb5
==================

DotWeb5 was invented by Wilmix Jemin J in 2013, evolving from Java and DOTWEB3.0. Earlier versions of Java (JDK 1.7 and JDK 1.8) were vulnerable to source code extraction using tools like JAD decompiler.
We are grateful to our friends, including Venkat, GitHub, and many others, for their support in this journey.


⚠️ Limitations of Java and C#
==============================

- Java .class files are easily decompiled using tools like JAD.
- This makes Java less secure for compiler development.
- DotWeb5 was created to overcome these limitations and is ideal for building data structures and compilers.
- It accepts .java7 files and translates them into DotWeb5 class files, which are incomprehensible to hackers.
- DotWeb5 is not focused on GUI development (e.g., Java Swing).

❓ Can You Build a Compiler Like Java?
=======================================

Yes. You can use Java to build a Java-like compiler or any other compiler. While some may criticize this approach, it is valid according to the principles of compiler design.
The same logic applies to building compilers for C or other languages.
However, I personally avoid GUI frameworks like Java Swing or J2EE due to misinformation spread by competitors or malicious actors, which could harm my products.


🛠️ My Compiler Design Journey
==============================

- At age 21, I built a compiler using VC++.
- Later, I developed a mini compiler in Java.

🚀 Why DotWeb5 Is More Advanced Than Other Languages
====================================================
- DotWeb5 and Java/J2EE are both fluent and expressive, like natural English.
- DotWeb5 helps reduce lines of code, improving productivity.
- Both follow camelCase conventions and integrate beautifully with IDEs like IntelliJ IDEA.
- The creator of DotWeb5 is not interested in robotics, as it may replace human roles.
- We support AI, but not robots.

📘 DotWeb5 Programming Modules
==============================

DotWeb5 is divided into two modules:
- DotWeb5 – Module 1
- DotWeb5 – Module 2

🔍 About DotWeb5 Modules
=========================

DotWeb5 keywords are designed to resemble those in Java, making it easy for Java professionals and companies to learn and adopt. While most syntax is familiar, DotWeb5 introduces several attractive and unique constructs.
DotWeb5 is used in:
- Console applications
- Web applications
- Machine learning
- Data science
- Remote X applications
Module 1 is primarily used by Java and DotWeb5 professionals. The Remote X Application module will be released after the Machine Learning and Data Science modules are finalized.

🔐 DotWeb5 Reserved Keywords – Module 1
========================================

DotWeb5 includes a set of reserved keywords that cannot be used as variable names, method names, class names, or other identifiers.

✅ Keyword Overview
===================
<Pre>
<code>
  <table bgcolor=black>
<JAVA7>       </JAVA7>       abstract       assert
boolean       break          byte           case
<CATCH>       char           <CLASS>        continue
default       do             double         else
enum          <---           final          <FINALLY>
float         for            if             -->
<IMPORT>      instanceof     int            interface
long          native         new            <PACKAGE>
private       protected      public         return
short         <SHARED>       <SUPER>        switch
synchronized  <IS>           throw          throws
transient     <TRY>          void           volatile
while
</table>
</code>
</pre>

🧪 Sample Program: testme.java7


<Pre>
<code>
  <table bgcolor=black>
    
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
    
 </table>
</code>
</Pre>



🖥️ Output
==========

<Pre>
<code>
  <table bgcolor=black>
    
Value is 15 
Under Weight is less than 15. Your health is worst = 5
Under Weight is less than 15. Your health is worst = 5
Note: Please enter accurately
java.lang.Exception
java.lang.Exception

  </table>
</code>
</Pre>


📘 DotWeb5 Reserved Keywords – Module 2
========================================

DotWeb5 includes a set of reserved keywords that cannot be used as variable names, method names, class names, or other identifiers. In Module 2, developers can build prototype software such as .exe files for console-based DotWeb5 programs. This module is designed to be familiar to DotWeb5 and Java/J2EE professionals.

🔐 Keyword Reference (Total: 50 Keywords)
=========================================

<Pre>
<code>
  <table bgcolor=black>
    
<ABSTRACT>       - Declares an abstract class  
<BREAK>          - Exits a loop  
<CASE>           - Used as an option in switch statements  
<CATCH>          - Handles exceptions  
<CLASS>          - Declares a class (collection of objects)  
<CONTINUE>       - Skips to the next loop iteration  
<DO> <WHILE>     - Creates a do-while loop  
<ELSE>           - Follows an <IF> condition  
<ENUM>           - Declares a group of constants  
<FINALLY>        - Executes regardless of exceptions  
<FOR>            - Creates a for loop  
<FOREACH>        - Iterates over collections (arrays, lists, sets)  
<GOTO>           - Jumps to labeled code  
<IF>             - Conditional logic  
is               - Checks object type compatibility  
<IN>             - Checks if an element exists  
<OBJECT>         - Represents an instance of a class  
<INTERFACE>      - Enables multiple inheritance  
<DEFAULT>        - Default case in switch statements  
<BASE>           - Calls base class methods  
<LOCK>           - Ensures thread-safe execution  
<PACK>           - Declares a package (namespace)  
<NEW>            - Instantiates a class  
<OPERATOR>       - Used for operator overloading  
<READONLY>       - Declares read-only variables  
<RET>            - Returns a value  
<SIZEOF>         - Returns memory size of a variable  
<TYPEOF>         - Gets the type of an object  
void             - Declares a method with no return value  
Shared           - Calls static methods without creating objects  
<STR>            - Represents a string  
<STRUCT>         - Declares a structured record  
<SWITCH>         - Selects among multiple code blocks  
<IS>             - Refers to the current object  
<TRY>            - Begins a try block  
<THROW>          - Throws an exception  
<USE>            - Imports DotWeb5 libraries or packages  
<VIRTUAL>        - Declares methods that can be overridden  
<VOLATILE>       - Enables synchronized variable access across threads  
<WHILE>          - Creates a while loop  
<JAVA7>          - Loads I/O packages for Java/J2EE compatibility  
<JAVA>           - Loads I/O packages for console/web apps  
<HEAPJ7>         - Stores large data objects to prevent memory overflow  
<CONVERTARRAYLIST> - Converts strings to ArrayList  
<OVERRIDE>       - Overrides parent class methods  
bool             - Boolean type (true/false)  
get / set        - Accessors for retrieving and assigning values  
<OAKJAVA7SECURITY> - Secures DotWeb5 executable files  

 </table>
</code>
</Pre>


💎 Diamond Modules
===================

DotWeb5 Module 1 and Module 2 together form the Diamond Module, which supports .java7 programs. When compiled using the WEBC7 compiler, a .java7 file will generate:
- .jclass file
- .exe file
WEBC7 is an open-source compiler available for DotWeb5 professionals to practice and build secure applications.

🔐 Security Module
===================
A third module focused on security is available in the DotWeb5 Enterprise Edition. It includes advanced features for protecting executable files and managing secure environments.

🧪 Example: Operator Overloading and Structure in DotWeb5
==========================================================
  
<Pre>
<code>
  <table bgcolor=black>
    
<CLASS> Calculator
{
  int a = 5;
  int b = 10;

  <OPERATOR> + (Calculator c1, Calculator c2)
  {
    Calculator result = <NEW> Calculator();
    result.a = c1.a + c2.a;
    result.b = c1.b + c2.b;
    <RET> result;
  }

  <STRUCT> display()
  {
    <PRINTLINE>("Sum A: " + a);
    <PRINTLINE>("Sum B: " + b);
  }
}

<MAIN>
{
  Calculator obj1 = <NEW> Calculator();
  Calculator obj2 = <NEW> Calculator();
  Calculator obj3 = obj1 + obj2;
  obj3.display();
}

 </table>
</code>
</Pre>


🖥️ Output
==========

<Pre>
<code>
  <table bgcolor=black>
    
Sum A: 10
Sum B: 20


     </table>
</code>
</Pre>




