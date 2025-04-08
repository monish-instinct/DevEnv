# DevEnv Android Library

Welcome to **DevEnv**, an Android library packaged as an `.aar` file for quick integration into your Android Studio projects.

---

## 📦 Download

👉 [Download the latest release (.aar)]([https://github.com/monish-instinct/DevEnv/releases/download/DevEnv/DevEnv.aar](https://github.com/monish-instinct/DevEnv/releases/download/DevEnv/app-release.aar))

---

## 🚀 How to Use the `.aar` in Your Android Project

### 1. Add the `.aar` to Your Project

- Download the `.aar` file from the [Releases page](https://github.com/monish-instinct/DevEnv/releases).
- Copy the `.aar` file into your app-level `libs/` folder. If it doesn't exist, create one.

### 2. Add It to Gradle

In your **app-level `build.gradle`** file:

```gradle
repositories {
    flatDir {
        dirs 'libs'
    }
}

dependencies {
    implementation(name: 'DevEnv', ext: 'aar')
}
