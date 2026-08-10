plugins {
    id 'com.android.application'
}

android {
    namespace 'com.jema.investments'
    compileSdk 35

    defaultConfig {
        applicationId "com.jema.investments"
        minSdk 23
        targetSdk 35
        versionCode 1
        versionName "1.0"
    }
}

dependencies {
    implementation 'androidx.appcompat:appcompat:1.7.0'
}
