# 神码再现 v3.6.7 Android App

## 项目结构

```
ShenMaApp/
├── build.gradle
├── settings.gradle
├── gradle.properties
├── gradle/wrapper/gradle-wrapper.properties
└── app/
    ├── build.gradle
    ├── proguard-rules.pro
    └── src/main/
        ├── AndroidManifest.xml
        ├── assets/index.html          <-- v3.6.7 已内置
        ├── java/com/xinghuishama/shenma/MainActivity.java
        └── res/
            ├── layout/activity_main.xml
            ├── values/strings.xml
            ├── values/themes.xml
            └── xml/network_security_config.xml
```

## 构建步骤

### 1. 用 Android Studio 打开
- 安装 Android Studio (https://developer.android.com/studio)
- Open -> 选择本项目文件夹
- 等待 Gradle Sync（首次约3-5分钟）

### 2. 添加图标（可选）
在 `app/src/main/res/` 对应目录放入图标：
- mipmap-mdpi/ic_launcher.png (48x48)
- mipmap-hdpi/ic_launcher.png (72x72)
- mipmap-xhdpi/ic_launcher.png (96x96)
- mipmap-xxhdpi/ic_launcher.png (144x144)
- mipmap-xxxhdpi/ic_launcher.png (192x192)

### 3. 运行或打包
- 手机连电脑开启USB调试，点击 Run 'app'
- 或 Build -> Generate Signed Bundle / APK -> APK

## 功能特点

- 内置 v3.6.7 HTML，无需网络即可打开
- 全屏沉浸，隐藏状态栏/导航栏
- 硬件加速，粒子特效流畅
- 下拉刷新原生支持
- LocalStorage 数据持久化
