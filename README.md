<div align="center">

<img src="https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white" alt="Android Studio"/>
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>
<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/>

# 📱 Android Studio Installation & Setup Guide
### *From Download to First App Execution*

![Version](https://img.shields.io/badge/Version-1.0-blue?style=flat-square)
![Year](https://img.shields.io/badge/Year-2026-orange?style=flat-square)
![Type](https://img.shields.io/badge/Type-Technical%20Documentation-green?style=flat-square)

---

**Submitted by:** Md. Mujahid Hasan  
**Department:** Cyber Security Engineering, UFTB  
**Submitted to:** Md. Abdullah — Lecturer, Dept. of Cyber Security Engineering, UFTB

</div>

---

## 📋 Table of Contents

1. [Introduction](#1-introduction)
2. [System Requirements](#2-system-requirements)
3. [Downloading Android Studio](#3-downloading-android-studio)
4. [Installing Android Studio](#4-installing-android-studio)
5. [First Launch Configuration](#5-first-launch-configuration)
6. [Creating a New Android Project](#6-creating-a-new-android-project)
7. [Gradle Sync](#7-gradle-sync)
8. [Creating an Android Emulator](#8-creating-an-android-emulator)
9. [Starting the Emulator](#9-starting-the-emulator)
10. [Running the Application](#10-running-the-application)
11. [Troubleshooting Guide](#11-troubleshooting-guide)
12. [Conclusion](#12-conclusion)

---

## 1. Introduction

This documentation provides a **complete step-by-step guide** for installing Android Studio, configuring the Android Emulator, and running your first Android application. It is intended for **beginners and students** who are setting up their Android development environment for the first time.

### 1.1 Objectives

- ✅ Download and install Android Studio on Windows
- ✅ Configure the Android SDK and required components
- ✅ Create and launch an Android Virtual Device (AVD)
- ✅ Create a new Android project and run it on the Emulator

### 1.2 Scope

This guide covers the complete installation workflow on a **Windows 10 or Windows 11 (64-bit)** machine. Steps may vary slightly on macOS or Linux.

---

## 2. System Requirements

Ensure your system meets the following minimum requirements before beginning installation:

| Requirement | Specification |
|---|---|
| 🖥️ **Operating System** | Windows 10 / Windows 11 (64-bit) |
| 🧠 **RAM** | Minimum 8 GB *(16 GB Recommended)* |
| 💾 **Storage** | 20 GB of Free Disk Space |
| ⚙️ **Processor** | Intel Core i5 / AMD Ryzen 5 or higher |
| ☕ **Java Development Kit** | Bundled with Android Studio (JDK 17) |
| 📦 **Android Studio Version** | Latest Stable Release *(Hedgehog or newer)* |
| 🔧 **Virtualization** | Intel VT-x or AMD-V *(required for Emulator)* |

---

## 3. Downloading Android Studio

### Step 1: Visit the Official Website

Open your web browser and navigate to the official Android Studio download page:

> 🔗 **URL:** [https://developer.android.com/studio](https://developer.android.com/studio)

### Step 2: Download the Installer

- Click the **Download Android Studio** button on the homepage
- Read and accept the **Terms and Conditions**
- The installer file will begin downloading:

```
android-studio-xxxx.exe
```

> 📸 *Screenshot: Android Studio download page*

---

## 4. Installing Android Studio

### Step 1: Run the Installer

Locate the downloaded `.exe` file and double-click it to begin installation:

```
android-studio-2024.x.x.x-windows.exe
```

> 💡 **Tip:** Right-click the installer and select **"Run as Administrator"** if prompted.

---

### Step 2: Welcome Screen

Click **Next** on the Android Studio Setup welcome screen.

> 📸 *Screenshot: Android Studio Setup welcome screen*

---

### Step 3: Select Components

On the **Choose Components** screen, ensure the following components are selected:

| # | Component | Status |
|---|---|---|
| 1 | Android Studio | ✅ Required |
| 2 | Android SDK | ✅ Required |
| 3 | Android Virtual Device (AVD) | ✅ Required |

> 📸 *Screenshot: Component Selection Screen*

---

### Step 4: Choose Installation Path

Choose the installation location. The **default path is recommended**:

```
C:\Program Files\Android\Android Studio
```

> 📸 *Screenshot: Installation path selection screen*

---

### Step 5: Complete Installation

Click **Install** and wait for the progress bar to complete.

> ⏱️ This may take **5–10 minutes** depending on your internet speed.

> 📸 *Screenshot: Installation progress bar*

---

## 5. First Launch Configuration

After installation, Android Studio will launch a **Setup Wizard** to configure the development environment.

### Step 1: Open Android Studio

Click **Finish** on the installer to launch Android Studio, or open it from the **Start Menu**.

---

### Step 2: Select Installation Type

On the Setup Wizard, select **Standard** and click **Next**.

> 📌 **Recommended:** Select **'Standard'** to automatically download all required SDK components.

> 📸 *Screenshot: Setup Wizard — Installation Type selection*

---

### Step 3: Choose UI Theme

Select your preferred editor theme:

| Theme | Description |
|---|---|
| 🌑 **Darcula** | Dark theme — recommended for long sessions |
| ☀️ **Light** | Classic light theme |

> 📸 *Screenshot: Theme selection screen*

---

### Step 4: SDK Components Download

Android Studio will automatically download and install the following components. **An active internet connection is required:**

- Android SDK
- SDK Build Tools
- Android Emulator
- Android SDK Platform Tools

> 📸 *Screenshot: SDK components download progress*

---

## 6. Creating a New Android Project

### Step 1: Start a New Project

From the Android Studio **Welcome Screen**, click **New Project**.

> 📸 *Screenshot: Android Studio Welcome Screen*

---

### Step 2: Select Project Template

Choose **Empty Activity** and click **Next**.

> 📸 *Screenshot: Project template selection — Empty Activity*

---

### Step 3: Configure Project Settings

Fill in the project configuration as follows:

| Field | Value |
|---|---|
| **Name** | `MyFirstApp` |
| **Package Name** | `com.example.myfirstapp` |
| **Save Location** | `C:\Users\YourName\AndroidStudioProjects\MyFirstApp` |
| **Language** | Kotlin |
| **Minimum SDK** | API 24 (Android 7.0 Nougat) |

> 💡 **Kotlin** is the official language for Android development, recommended by Google.

> 📸 *Screenshot: Project configuration settings*

---

### Step 4: Finish

Click **Finish** to create the project. Android Studio will open the project workspace.

> 📸 *Screenshot: Android Studio project workspace*

---

## 7. Gradle Sync

After the project is created, Android Studio will automatically begin **Gradle Sync** to download dependencies.

### What is Gradle?

> Gradle is the **build automation tool** used by Android Studio. It downloads required libraries and compiles your project.

### Monitoring Sync Status

Watch the status bar at the bottom of the screen:

| Status | Indicator |
|---|---|
| ⏳ Syncing | `Gradle Sync Started...` |
| ✅ Complete | `Gradle Sync Finished` |

> 📸 *Screenshot: Gradle sync status bar*

---

## 8. Creating an Android Emulator

An **Android Virtual Device (AVD)** simulates a real Android device on your computer, allowing you to test apps without a physical device.

### Step 1: Open Device Manager

Navigate to:

```
Tools → Device Manager
```
*(or click the Device Manager icon in the toolbar)*

---

### Step 2: Create a New Device

Click the **`+ Create Device`** button.

---

### Step 3: Select Hardware Profile

Choose a device from the list:

- **Category:** Phone
- **Device:** Pixel 7 *(recommended)*

> 📸 *Screenshot: Hardware profile selection — Pixel 7*

---

### Step 4: Select System Image

Choose the Android version for your emulator:

| Field | Value |
|---|---|
| **Recommended** | Android 15 (API Level 35) |
| **Release Name** | VanillaIceCream |
| **Target** | Google APIs |
| **ABI** | x86_64 |

> ⚠️ If the system image is not already downloaded, click the **Download** link next to it and wait for the download to complete.

> 📸 *Screenshot: System image selection screen*

---

### Step 5: Finish Configuration

Review the AVD configuration and click **Finish**. Your emulator device will now appear in the **Device Manager** list.

> 📸 *Screenshot: AVD configuration summary*

---

## 9. Starting the Emulator

### Step 1: Launch from Device Manager

In the Device Manager, locate your newly created device **(Pixel 7 API 35)** and click the **Play button (▶)** to start it.

> 📸 *Screenshot: Device Manager with Play button*

---

### Step 2: Wait for Boot

The emulator will open in a separate window and boot the Android operating system.

> ⏱️ The **first boot may take 2–5 minutes**. Please be patient.

> 📸 *Screenshot: Android emulator booting*

---

## 10. Running the Application

### Step 1: Select the Emulator as Target Device

In the toolbar at the top of Android Studio, click the device dropdown and select:

```
Pixel 7 API 35
```

---

### Step 2: Run the Application

Click the **Run** button in the toolbar, or use the keyboard shortcut:

| Method | Action |
|---|---|
| 🖱️ **Run Button** | Click ▶ in the toolbar |
| ⌨️ **Keyboard Shortcut** | `Shift + F10` |

---

### Step 3: Expected Output

After a successful build, the application will launch on the emulator. The default output for an **Empty Activity** project is:

```
✅ Hello Android!
```

> 📸 *Screenshot: App running on Android emulator — "Hello Android!" output*

---

## 11. Troubleshooting Guide

Below are common issues you may encounter and their recommended solutions:

| ⚠️ Problem | ✅ Solution |
|---|---|
| **Gradle Sync Failed** | Go to `File → Sync Project with Gradle Files`. Check your internet connection. |
| **Android SDK Not Found** | Go to `Tools → SDK Manager` and install the missing SDK platform. |
| **Emulator Not Starting** | Enable **Virtualization Technology** (VT-x / AMD-V) in BIOS settings. |
| **HAXM Error on Startup** | Install Intel HAXM from `SDK Manager → SDK Tools` tab. |
| **App Build Failed** | Check the **Build Output** tab at the bottom of Android Studio for error details. |
| **Emulator is Very Slow** | Increase RAM allocation for AVD in Device Manager or use a lower API level. |
| **Device Not Found in Run Config** | Restart the emulator and wait for it to **fully boot** before running the app. |

---

## 12. Conclusion

This documentation has covered the **complete process** of setting up a fully functional Android development environment — from downloading Android Studio to executing your first application on an Android Emulator.

### ✅ Summary of Steps Completed

- [x] Downloaded Android Studio from the official Google website
- [x] Installed Android Studio with all required components
- [x] Completed first-launch configuration and SDK download
- [x] Created a new Android project using Kotlin and Empty Activity template
- [x] Configured and launched an Android Virtual Device (AVD)
- [x] Successfully built and deployed the first Android application

---

### 🎉 Next Steps

Now that your environment is set up, here's what to explore next:

- 📖 Learn **Kotlin basics** — variables, functions, classes
- 🎨 Build your first custom UI using **Jetpack Compose** or **XML layouts**
- 🔧 Try modifying the `MainActivity.kt` file and see live changes
- 📱 Explore the **Android Developer documentation** at [developer.android.com](https://developer.android.com)

---

<div align="center">

*Android Studio Installation & Setup Guide — Technical Documentation*  
**University of Frontier Technology, Bangladesh | Cyber Security Engineering | 2026**

</div>
