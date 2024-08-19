# Java - Features, Functions, and Data Structures

``` Java
System.out.println("Hello World!");
```

## Getting Started

- Install
    - Mac
        1. Install Java Runtime Environment (JRE): https://www.java.com/en/download/
        2. Install JDK: https://www.oracle.com/java/technologies/downloads/
- Executing Java Code
    1. Create a <class>.java source code file with a .java extension
    
    ```java
    touch Test.java
    ```
    
    1. Compile the source files into .class files (bytecodes - machine language of the Java VM) by the javac compiler
    
    ```java
    javac Test.java 
    ```
    
    1. Run the Java application with the instance of the Java Virtual Machine
    
    ```java
    java Test.java
    ```
    
- About
    - Java is both a programming language and platform
- Characteristics
    - High-level language
    - Object-Oriented
    - Portable
    - High-performance
    - Multithreaded
    - Distributed
    - Architecture neutral
    - Robust, Secure, Dynamic, and Simple
- Java Platform (Java Virtual Machine - JVM)
    - A *platform* is the hardware or software env. in which a program runs, such as Mac OS, Windows, and Linux.
    - Java is a software-only platform that runs on top of other hardware-based platforms.
    - The Java Platform has two components:
        - Java Virtual Machine
        - Java Application Programming Interface (API) - predefined java libraries/packages.
    - Slower than native code but advancing compilers and VMs are making them close.
- Java Tools
    - Development Tools - Debugging, compiling, monitoring, documenting, etc. with the javac compiler, java launcher, and javadoc documentation.
    - API - Predefined libraries of useful classes for your own applications, such as DB access, networking and security, etc.
    - Deployment technology
    - User Interface Toolkits - like JavaFX, Swing, and Java 2D for GUI.
    - Integration libraries for DB access and manipulation of remote objects.
- Distribution:
    - With Java Web Start software, users will be able to launch your applications with a single click of the mouse.
    - An automatic version check at startup ensures that users are always up to date with the latest version of your software.
    - If an update is available, the Java Web Start software will automatically update their installation.