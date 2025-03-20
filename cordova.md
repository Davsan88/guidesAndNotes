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

### 6️⃣ **Remove a Platform**
```sh
cordova platform remove android
```

---


## 🔌 **Cordova Plugins (Access Native Features)**
Cordova uses **plugins** to allow **JavaScript** to interact with **native device capabilities**.

### 1️⃣ **Installing Plugins**
```sh
cordova plugin add <plugin-name>
```
For example, to install the **Camera plugin**:
```sh
cordova plugin add cordova-plugin-camera
```

### 2️⃣ **Listing Installed Plugins**
```sh
cordova plugin ls
```

### 3️⃣ **Removing a Plugin**
```sh
cordova plugin remove <plugin-name>
```

### 4️⃣ **Using Plugins in JavaScript**
Example: **Using the Camera Plugin**
```js
declare var navigator: any; // Required for Cordova plugins

function takePhoto() {
    navigator.camera.getPicture(
        (imageData) => {
            console.log("Photo taken:", imageData);
        },
        (err) => {
            console.error("Camera error:", err);
        },
        { quality: 50, destinationType: navigator.camera.DestinationType.DATA_URL }
    );
}
```

---


## 📲 **Popular Cordova Plugins**
| Plugin | Purpose |
|---------|---------|
| `cordova-plugin-camera` | Access device camera |
| `cordova-plugin-geolocation` | Get user location |
| `cordova-plugin-file` | Read/write files |
| `cordova-plugin-device` | Get device info |
| `cordova-plugin-network-information` | Check network status |
| `cordova-plugin-fcm-with-dependecy-updated` | Push notifications (Firebase) |

---


## 🛠 **Debugging Cordova Apps**

### 1️⃣ **Console Logging in Cordova**
Since Cordova apps run on **mobile devices**, debugging isn't as simple as using `console.log()`. Instead, use **remote debugging**:

#### **Android: Use Chrome DevTools**
```sh
chrome://inspect
```
Connect your **Android device** and **debug remotely**.

#### **iOS: Use Safari Web Inspector**
```sh
Develop > Your App > Inspect
```

