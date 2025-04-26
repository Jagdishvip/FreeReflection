# ✨『 ↺ Jagdish VIP ↻ 』✨

## 🔥 FreeReflection (Unrestricted Reflection API)

**FreeReflection** is a powerful Android library created by **Jagdish VIP** that allows you to freely use Reflection APIs without restrictions on Android P, Q, R, and newer.

---

## 🚀 How to Use?

### Step 1: Add JitPack repository
In your project's root `build.gradle`:
```gradle
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

### Step 2: Add Dependency
In your app's `build.gradle`:
```gradle
implementation 'com.github.Jagdishvip:FreeReflection:3.1.0'
```

### Step 3: Initialize Reflection
Inside your `Application` class:
```java
@Override
protected void attachBaseContext(Context base) {
    super.attachBaseContext(base);
    Reflection.unseal(base);
}
```

**That's it!** Now, all reflection restrictions are gone, and you can enjoy using reflection APIs freely!

---

## 📖 Under the Hood (References)
- [Free reflection above Android P](http://weishu.me/2018/06/07/free-reflection-above-android-p/)
- [Another way to bypass reflection API restrictions](http://weishu.me/2019/03/16/another-free-reflection-above-android-p/)

---

## 🙏 Support & Donation
If you like **FreeReflection** and appreciate my efforts, feel free to buy me a coffee!

**Bitcoin**: `39Wst8oL74pRP2vKPkPihH6RFQF4hWoBqU`

---

## ⚖️ License
[MIT License](LICENSE)

---

🌟 **Developed and Maintained by**  
✨『 ↺ **Jagdish VIP** ↻ 』✨ © 2024
