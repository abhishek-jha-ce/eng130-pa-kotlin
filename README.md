# Kotlin

Kotlin is a cross-platform, statically typed, general-purpose programming language.
<img align="right" width="450" height="184" src="https://user-images.githubusercontent.com/110366380/207404210-02364cff-e782-4626-a573-e0a838f2ca39.jpg">

- It is Open-source.
- Static language (Declaration required e.g. int var = value).
- Designed & developed by `JetBrains`.
- Supports both object-oriented and functional programming.
- Runs on the Java Virtual Machine (JVM).
- Syntax similar to languages such as Java, C#, Scala etc.

The name `Kotlin` is based on a Russian island, located near the head of the Gulf of Finland.

Kotlin is `inter-operable` with the Java Programming language. We can easily convert between `Kotlin` and `Java` codes.
- There is also an automatic Java-to-Kotlin converter built into Android Studio.

## Advantage of Kotlin over Java
- Fewer lines of codes.
- Faster Compilation.
- Much simpler and more understandable structure.
- We can also develop Web, Desktop and Android Applications with Kotlin, same like Java.

![features_kotlin-1](https://user-images.githubusercontent.com/110366380/207405694-c85e7446-1b16-46d9-b48d-d80e5f1025d0.jpg)

## Android

<img align="right" width="300" height="206" src="https://user-images.githubusercontent.com/110366380/207403348-4f9a1981-69b0-4178-89fc-1b7118036dd5.jpg">

Android is an Operating System designed for use on touchscreen Mobile Devices such as smartphones and tablets. It is based on a modified version of the Linux kernel and other open-source software, designed primarily for touchscreen mobile devices such as smartphones and tablets.
- It was originally developed as an advanced operating systems for digital cameras.
- It is also used as an OS in Televisions, Smartwatches, Android Auto and Wear devices.
- Used in more than 100 Languages.

# Installations Required

## Java Development Kit (JDK)
<img align="right" width="420" height="240" src="https://user-images.githubusercontent.com/110366380/207402187-1bab76d7-69ce-43e1-ad54-18725b778952.jpeg">

**Java Development Kit (JDK)** implements the Java Language Specification (JLS) and the Java Virtual Machine Specification (JVMS) and provides the Standard Edition (SE) of the Java Application Programming Interface (API).

**Java virtual machine (JVM)** is a virtual machine that enables a computer to run Java programs as well as programs written in other languages that are also compiled to Java bytecode like `kotlin`.

**Java Runtime Environment (JRE)** is a software layer that runs on top of a computer’s operating system software and provides the class libraries and other resources that a specific Java program needs to run. It contains the *Java class libraries*, the *Java class loader*, and the *Java virtual machine*.
- The **class loader** is responsible for correctly loading classes and connecting them with the core Java class libraries.
- The **JVM** is responsible for ensuring Java applications have the resources they need to run and perform well in your device or cloud environment.
- The **JRE** is mainly a container for those other components, and is responsible for orchestrating their activities.

Together, the **Java Development Kit (JDK)**, the **Java Virtual Machine (JVM)**, and the **Java Runtime Environment (JRE)** form a powerful trifecta of Java for developing and running Java applications. They all work together to let developers build and run Java programs. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/110366380/207308467-42bb57c7-9928-4830-b26a-a8fd3fc3283b.png">
  <strong><em>Figure 1: Java Development Kit Architecture</em></strong>
</p>

### Installing JDK

- We can install JDK from https://jdk.java.net/.
- Click on the latest release from **Ready for use:** section.
- In the next page, Download the **Builds** for the required OS.
- For **Windows**, it will download a zip file. Once downloaded extract the files.
- Copy the folder and paste it in `C:\Program Files\Java`. If `Java` folder doesn't exist create a new one.
- Edit the `environment variables` and add path for java to it.
  -  Right click on windows and select `System`.
  -  Select `Advanced system settings` tab.
  -  A new pop up windows will open, click on `Environment Variables`.
  -  Another pop up window will open. In the bottom section (System variables), select `Path` and click on `Edit`.
  -  Click on new, and add `C:\Program Files\Java\jdk-<version>\bin` to the path. This is where the `Java` Application is located.

## Android Studio

<img align="right" title="Android logo" src="https://user-images.githubusercontent.com/110366380/207345087-51ac667f-1dd0-4844-9193-59afa6358172.png">

Android Studio is the **official Integrated Development Environment (IDE)** for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development. It is available for download on Windows, macOS and Linux based operating systems.

An **IDE** is a software application that provides comprehensive facilities to developers for software development. An IDE normally consists of at least:
- A Source Code Editor
- Build Automation Tools
- A Debugger.

### Installing Android Studio
<img align="right" width="533" height="300" src="https://user-images.githubusercontent.com/110366380/207400599-72720728-50e1-424f-ad01-f8ad2618a5f1.jpg">

- We can install Android Studio from https://developer.android.com/studio.
- Click on `Download Android Studio`. It will download the most up-to-date version.
- **Note**: A minimum of `8 GB RAM` is required. It also doesn't support 32-bit system after version 4 or above.
- Install the downloaded `.exe` file.
- The latest android version already come packaged with a `jdk` so we might not need to install jdk if using android studio.
- The latest version of android studio as of Dec 2022 is `Dolphin | 2021.3.1`
