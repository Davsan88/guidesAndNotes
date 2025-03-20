# 🚀 **Apache Cordova Reference Guide**

## 📌 **What is Cordova?**
Apache **Cordova** is an **open-source mobile development framework** that allows developers to create mobile apps using **web technologies** (**HTML, CSS, JavaScript**). It acts as a **bridge** between web applications and **native device features** like the **camera, GPS, file system,** and **push notifications**.

### ✅ **Why use Cordova?**
- Allows **web developers** to create **mobile apps** without learning **native languages** (*Java/Kotlin for Android, Swift for iOS*).
- Provides **plugins** to access **native device features**.
- Enables **deployment** on **multiple platforms** (*Android, iOS, Windows*).

---


## 🔧 **Setting Up Cordova**

### 1️⃣ **Install Cordova CLI**
To install Cordova globally, run:

```sh
npm install -g cordova
```

### 2️⃣ **Create a New Cordova Project**
```sh
cordova create myApp com.example.myapp MyApp
cd myApp
```

### 3️⃣ **Add a Platform (Android/iOS)**
```sh
cordova platform add android  # For Android
cordova platform add ios  # For iOS (Mac required)
```

### 4️⃣ **Run the App on a Device/Emulator**
```sh
cordova run android --device  # Run on a real Android device
cordova run ios --device  # Run on a real iOS device
```

### 5️⃣ **Check Installed Platforms**
```sh
cordova platform ls
```