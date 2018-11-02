# AndroidConfigGradle

## 1. 引用 Gradle 文件

``` gradle
apply from: "http://www.wanandroid.com/tools/mockapi/2793/config_gradle"
```

## 2. compileSdkVersion

``` gradle
compileSdkVersion rootProject.ext.android.compileSdkVersion
```

## 3. defaultConfig

``` gradle
minSdkVersion rootProject.ext.android.minSdkVersion
targetSdkVersion rootProject.ext.android.targetSdkVersion
versionCode Integer.parseInt(VERSION_CODE)
versionName VERSION_NAME
```

## 4. dependencies

``` gradle
implementation rootProject.ext.dependencies.appcompat_v7
api rootProject.ext.dependencies.AppBaseModule
```
