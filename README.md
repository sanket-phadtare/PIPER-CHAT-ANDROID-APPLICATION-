# 🗣️ PIPER-CHAT — Messenger Application Using Android

### 🚀 Overview
PIPER-CHAT is an Android-based chat application inspired by WhatsApp, designed to **eliminate language barriers** in online communication.  
It enables real-time **language detection**, **translation**, and **secure messaging** between users across different countries.

---

### 🎯 Aim of the Project
- To help people communicate seamlessly across countries without language hesitation.  
- Automatically detect the language of incoming messages.  
- Translate messages into the user’s native language.  
- Provide **end-to-end encryption** for secure communication.

---

### 🧠 Example Use Case
A German manager can easily communicate with Indian clients.  
Messages received in German are automatically **detected** and **translated** into English (or any preferred language).

---

### 💻 Front-End Implementation
**Tools Used:**
- XML Coding  
- Adobe XD  

**Widgets Used:**
- `Button` — Push-button for UI interactions  
- `ImageView` — Display images  
- `Toast` — Show quick notifications  
- `EditText` — Input text field  
- `AlertDialog` — Confirmation dialogs  

---

### ⚙️ Back-End Implementation
**Technologies:**
- Firebase (Authentication, Realtime Database, Cloud Messaging, Crash Reporting, Hosting)
- Machine Learning (Google ML Kit)

**Firebase Benefits:**
- Easy authentication and hosting  
- Real-time database sync  
- Cloud messaging and remote configuration  
- Crash reporting and test lab integration  

---

### 🤖 Machine Learning Integration

**What is Machine Learning?**  
Machine Learning (ML) is a subset of Artificial Intelligence (AI) that allows systems to automatically learn and improve from experience without explicit programming.  
In **PIPER-CHAT**, ML is used for **language detection** and **translation** to eliminate communication barriers between users speaking different languages.

---

### 🧩 Language Identification
ML Kit can identify over **100+ languages** using its `language-id` API.  
It provides confidence scores and returns the most likely language of the given text.

**Dependency:**
```gradle
implementation 'com.google.mlkit:language-id:16.1.1'

