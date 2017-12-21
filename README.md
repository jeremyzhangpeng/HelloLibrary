# HelloLibrary
在主工程中 build.gradle 中添加

allprojects {
    repositories {
        google()
        jcenter()
        maven { url "https://jitpack.io" }
    }
}

app build.gradle中添加
implementation 'com.github.jeremyzhangpeng:HelloLibrary:latest version'
