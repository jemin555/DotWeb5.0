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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>DotWeb5 Reserved Keywords – Module 2</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      padding: 20px;
    }
    h1 {
      color: #333;
      text-align: center;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
      background-color: #fff;
    }
    th, td {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: left;
      vertical-align: top;
    }
    th {
      background-color: #e0e0e0;
    }
    tr:nth-child(even) {
      background-color: #f9f9f9;
    }
    caption {
      caption-side: top;
      font-size: 1.2em;
      margin-bottom: 10px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <h1>DotWeb5 Reserved Keywords – Module 2</h1>

  <table>
    <caption>Keyword Reference Table</caption>
    <tr>
      <th>Keyword</th>
      <th>Description</th>
    </tr>
    <tr><td>&lt;ABSTRACT&gt;</td><td>Declares an abstract class</td></tr>
    <tr><td>&lt;BREAK&gt;</td><td>Exits a loop</td></tr>
    <tr><td>&lt;CASE&gt;</td><td>Used as an option in switch statements</td></tr>
    <tr><td>&lt;CATCH&gt;</td><td>Handles exceptions</td></tr>
    <tr><td>&lt;CLASS&gt;</td><td>Declares a class (collection of objects)</td></tr>
    <tr><td>&lt;CONTINUE&gt;</td><td>Skips to the next loop iteration</td></tr>
    <tr><td>&lt;DO&gt; &lt;WHILE&gt;</td><td>Creates a do-while loop</td></tr>
    <tr><td>&lt;ELSE&gt;</td><td>Follows an &lt;IF&gt; condition</td></tr>
    <tr><td>&lt;ENUM&gt;</td><td>Declares a group of constants</td></tr>
    <tr><td>&lt;FINALLY&gt;</td><td>Executes regardless of exceptions</td></tr>
    <tr><td>&lt;FOR&gt;</td><td>Creates a for loop</td></tr>
    <tr><td>&lt;FOREACH&gt;</td><td>Iterates over collections (arrays, lists, sets)</td></tr>
    <tr><td>&lt;GOTO&gt;</td><td>Jumps to labeled code</td></tr>
    <tr><td>&lt;IF&gt;</td><td>Conditional logic</td></tr>
    <tr><td>is</td><td>Checks object type compatibility</td></tr>
    <tr><td>&lt;IN&gt;</td><td>Checks if an element exists</td></tr>
    <tr><td>&lt;OBJECT&gt;</td><td>Represents an instance of a class</td></tr>
    <tr><td>&lt;INTERFACE&gt;</td><td>Enables multiple inheritance</td></tr>
    <tr><td>&lt;DEFAULT&gt;</td><td>Default case in switch statements</td></tr>
    <tr><td>&lt;BASE&gt;</td><td>Calls base class methods</td></tr>
    <tr><td>&lt;LOCK&gt;</td><td>Ensures thread-safe execution</td></tr>
    <tr><td>&lt;PACK&gt;</td><td>Declares a package (namespace)</td></tr>
    <tr><td>&lt;NEW&gt;</td><td>Instantiates a class</td></tr>
    <tr><td>&lt;OPERATOR&gt;</td><td>Used for operator overloading</td></tr>
    <tr><td>&lt;READONLY&gt;</td><td>Declares read-only variables</td></tr>
    <tr><td>&lt;RET&gt;</td><td>Returns a value</td></tr>
    <tr><td>&lt;SIZEOF&gt;</td><td>Returns memory size of a variable</td></tr>
    <tr><td>&lt;TYPEOF&gt;</td><td>Gets the type of an object</td></tr>
    <tr><td>void</td><td>Declares a method with no return value</td></tr>
    <tr><td>Shared</td><td>Calls static methods without creating objects</td></tr>
    <tr><td>&lt;STR&gt;</td><td>Represents a string</td></tr>
    <tr><td>&lt;STRUCT&gt;</td><td>Declares a structured record</td></tr>
    <tr><td>&lt;SWITCH&gt;</td><td>Selects among multiple code blocks</td></tr>
    <tr><td>&lt;IS&gt;</td><td>Refers to the current object</td></tr>
    <tr><td>&lt;TRY&gt;</td><td>Begins a try block</td></tr>
    <tr><td>&lt;THROW&gt;</td><td>Throws an exception</td></tr>
    <tr><td>&lt;USE&gt;</td><td>Imports DotWeb5 libraries or packages</td></tr>
    <tr><td>&lt;VIRTUAL&gt;</td><td>Declares methods that can be overridden</td></tr>
    <tr><td>&lt;VOLATILE&gt;</td><td>Enables synchronized variable access across threads</td></tr>
    <tr><td>&lt;WHILE&gt;</td><td>Creates a while loop</td></tr>
    <tr><td>&lt;JAVA7&gt;</td><td>Loads I/O packages for Java/J2EE compatibility</td></tr>
    <tr><td>&lt;JAVA&gt;</td><td>Loads I/O packages for console/web apps</td></tr>
    <tr><td>&lt;HEAPJ7&gt;</td><td>Stores large data objects to prevent memory overflow</td></tr>
    <tr><td>&lt;CONVERTARRAYLIST&gt;</td><td>Converts strings to ArrayList</td></tr>
    <tr><td>&lt;OVERRIDE&gt;</td><td>Overrides parent class methods</td></tr>
    <tr><td>bool</td><td>Boolean type (true/false)</td></tr>
    <tr><td>get / set</td><td>Accessors for retrieving and assigning values</td></tr>
    <tr><td>&lt;OAKJAVA7SECURITY&gt;</td><td>Secures DotWeb5 executable files</td></tr>
  </table>

</body>
</html>

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


Note:
=====

This Dotweb5.0 tutorial is under construction



