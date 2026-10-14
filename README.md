# 📚 Deploying The RTVV – Reading Teaching Vocabulary Visualizer

> **Version:** 1.4 (Final Release)
> **Built with:** Flutter (Android SDK 34, Java 21)
> **Platform:** Android
> **License:** Open Source (Educational Research Project)

---

## 🎯 **Project Overview**

**Reading Teaching Vocabulary Visualizer (RTVV)** is an Android application developed as part of a research and deployment project.
The main goal of this project was to **build a word-scanning app** that helps **teachers, students, and researchers** analyze vocabulary from children’s reading materials.

The app extracts text from book pages using **Google ML Kit OCR**, identifies **sight words**, highlights vocabulary frequency, and supports classroom learning and language research.

The project also focuses on:

- Improving **usability and accuracy** of OCR-based text recognition.
- Iteratively **updating and refining app features** through multiple versions.
- Delivering a **stable, bug-free final release (v1.4)** suitable for public use.

---

## 🌟 **Key Features**

### 1. 📷 Scan and Analyze Text

- Use your device’s camera to capture a book page.
- Extract and process text in real time.
- Display word frequency statistics to help teachers analyze student reading materials.

### 2. 🧩 CPB Sight Words

- Includes a built-in **Children’s Picture Book (CPB) Sight Word** list.
- Automatically highlights and color-codes recognized words based on frequency.

### 3. 🆕 Vocabulary Checker *(Introduced in v1.2, Improved in v1.4)*

- Checks extracted words against preloaded vocabulary lists.
- Highlights **unknown or rare words** not found in the selected sight word set.
- Optimized for quick scanning and educational word visualization.

### 4. 📊 Word Frequency Report

- Generates **frequency counts** for all recognized words.
- Results can be shared or saved locally for analysis and classroom discussion.

### 5. 🧠 User-Friendly Interface

- Clean, minimal interface optimized for teachers and students.
- Simple navigation between scanning, viewing, and reporting features.

---

## 📱 **Installation Guide (Android 13 and Above)**

### Step 1 – Download the APK

➡️ [**Click here to download the latest APK (v1.4)**](https://github.com/Krishnaprasad2004/Deploying-The-RTVV/releases/download/v1.4_apk/RTVV.1.4.apk)

---

### Step 2 – Allow Installation from Unknown Sources

If prompted:
> “For your security, your phone is not allowed to install unknown apps.”

1. Tap **Settings**.
2. Enable **Allow from this source** for your browser or file manager.
3. Re-open the downloaded file to install.

---

### Step 3 – Install the App

1. Tap **Install** when prompted.
2. Wait for installation to finish.
3. Tap **Open** to launch the RTVV app.

✅ You’re ready to start scanning and analyzing words!

---

## 🔧 **Technical Details**

| Specification       | Details                                                                                          |
| ------------------- | ------------------------------------------------------------------------------------------------ |
| **Framework**       | Flutter                                                                                          |
| **Android SDK**     | API Level 34                                                                                     |
| **Java Version**    | Java 21                                                                                          |
| **Core Libraries**  | `google_mlkit_text_recognition`, `image_picker`, `url_launcher`, `csv`, `share`, `path_provider` |
| **Build Type**      | Release (APK)                                                                                    |
| **Platform Target** | Android Phones/Tablets                                                                           |

---

## 🧩 **Version History**

| Version  | Description                                                                       | Status                |
| -------- | --------------------------------------------------------------------------------- | --------------------- |
| **v1.0** | Prototype version with base OCR text recognition and sight word detection.        | ✅ Completed           |
| **v1.1** | Revised version with improved UI and bug fixes.                                   | ✅ Completed           |
| **v1.2** | Introduced the new *Vocabulary Checker* feature.                                  | ✅ Completed           |
| **v1.3** | Addressed performance issues and UI clutter.                                      | ⚠️ Minor bugs present |
| **v1.4** | Final release – optimized performance, refined vocabulary feature, no known bugs. | 🏁 Stable              |

---

## 🧠 **Challenges Faced & Solutions**

1. **Gradle and SDK Conflicts** – Resolved by aligning Android SDK 34 with Java 21 and upgrading Gradle plugin.
2. **ML Kit Dependency Overlaps** – Fixed by standardizing on `google_mlkit_text_recognition`.
3. **App Logo Scaling Issues** – Rebuilt launcher icons at 1024×1024 resolution.
4. **Release Signing Errors** – Corrected keystore path configuration in `key.properties`.
5. **GitHub Pages Setup** – Adjusted source folder to `/docs` for live public download page.
6. **Vocabulary Checker Lag** – Optimized using asynchronous background processing for smooth UI performance.

---

## 👥 **Project Collaborators**

| Role           | Name                 | Affiliation                                              |
| -------------- | -------------------- | -------------------------------------------------------- |
| **Client 1**   | *Dr. Clarence Green* | Professor of English Language Education, Hong Kong       |
| **Client 2**   | *Kathleen Keogh*     | Senior Lecturer, Information Technology, Ballarat        |
| **Supervisor** | *Bhavna Antony*      | Professor, Information Technology, Federation University |

---

## 🙌 **Credits**

Developed by the **WordScan Team**
**Krishnaprasad**, **Hassam**, **Kevin Alexander**, **Basil James**, **Khushmeet Kaur**

---

## 🚀 **Changelog**

| Version  | Date      | Updates                                                      |
| -------- | --------- | ------------------------------------------------------------ |
| **v1.4** | Oct 2025  | Final stable release, optimized performance, no known bugs   |
| **v1.3** | Oct 2025  | Fixed minor interface clutter and improved word highlighting |
| **v1.2** | Sept 2025 | Added Vocabulary Checker feature                             |
| **v1.1** | Aug 2025  | Bug fixes and UI improvement                                 |
| **v1.0** | July 2025 | Prototype build and first APK release                        |

---

## 🔗 **Quick Links**

- 🌍 [Download APK](https://github.com/Krishnaprasad2004/Deploying-The-RTVV/releases/download/v1.4_apk/RTVV.1.4.apk)
- 📦 [GitHub Repository](https://github.com/Krishnaprasad2004/Deploying-The-RTVV)
- 🎥 [Demonstration Video](https://youtu.be/eEuV8li9TJc)

---

> *Built with ❤️ using Flutter and Google ML Kit – Final Release v1.4*
