# Getting Started using Kotlin Desktop Application using Compose for Desktop

## What will be covered

In this tutorial, we will cover:
- Overview of Kotlin Desktop Application Development using 
Compose for Desktop
- Prerequisites
- Steps to create a **"Hello World"** Desktop Application using Compose for Desktop

## Overview
Fast reactive desktop UIs for Kotlin, based on Google's 
modern UI toolkit and brought to you by JetBrains. Compose simplifies and accelerates the UI development for desktop 
applications. It also allows UI code sharing between Android and Desktop applications.

Compose for Desktop can produce applications for macOS, Linux, and Windows platforms.

## Prerequisites
To create a Kotlin Desktop Application using Compose for Desktop, we have to use IntelliJ IDEA Community Edition or 
Ultimate Edition 20.2 or later.

You can download it from this link: [https://www.jetbrains.com/idea/](https://www.jetbrains.com/idea/)

## Create a new project
Follow the below steps to create a Kotlin Desktop Application using Compose for Desktop.

**Step 1:** Open IntelliJ IDEA IDE and click on New Project.

**Step 2:** A new project wizard will open up.
1. Select **Kotlin** from the left panel
2. Set the Project Name and Location
3. In the **Project Template** section choose **Desktop uses Kotlin** under **Jetpack Compose for Desktop**
4. Project **JDK** must be **at least JDK 11**
5. Set your Artifact Coordinates
6. Click on Next

![777x1046//KDAJC-1.4-Screenshot-1](https://github.com/AvijitKarmakar/Kotlin-Desktop-Application-Jetpack-Compose-Tutorial/blob/data/website/data/screenshots/KDAJC-1.4-Screenshot-1.png)

**Step 3:** Now you have to set some more things.
1. The **Template** will be **Compose Desktop Application**
2. Set your Test Framework
3. Target JVM version must be at least 11
4. Click on Finish

![777x1045//KDAJC-1.4-Screenshot-2](https://github.com/AvijitKarmakar/Kotlin-Desktop-Application-Jetpack-Compose-Tutorial/blob/data/website/data/screenshots/KDAJC-1.4-Screenshot-2.png)

After the creation of this project, you will see a sample code already written in the **main.kt** file. Please take 
the reference of the below screenshot.

![1037x1915//KDAJC-1.4-Screenshot-3](https://github.com/AvijitKarmakar/Kotlin-Desktop-Application-Jetpack-Compose-Tutorial/blob/data/website/data/screenshots/KDAJC-1.4-Screenshot-3.png)

Also, check the **build.gradle.kts** file.

![1037x1915//KDAJC-1.4-Screenshot-4](https://github.com/AvijitKarmakar/Kotlin-Desktop-Application-Jetpack-Compose-Tutorial/blob/data/website/data/screenshots/KDAJC-1.4-Screenshot-4.png)

You can update the compose version in this file. To check the latest version of Compose for Desktop follow this link:
[https://github.com/JetBrains/compose-jb/tags](https://github.com/JetBrains/compose-jb/tags). You can also update the 
Kotlin version with a compatible version with Compose.

## Run your project
You can run the project in multiple ways.

**Way 1:** By clicking on the run icon available at the left side of the **main** function

**Way 2:** By double-clicking on the run Gradle task. To find it follow this path: Gradle in Right Panel 🠖 HelloWorld
🠖 Tasks 🠖 compose desktop 🠖 run

After running the project, you will see an application opened up and showing a button with the text “Hello, World!” 
and if you click on it, the button text will be changed to “Hello, Desktop!”.

[https://youtu.be/FUCFVh3-q2k](https://youtu.be/FUCFVh3-q2k)