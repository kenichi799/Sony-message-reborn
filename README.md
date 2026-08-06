# Sony-message-reborn
​📱 About This Project
​This project contains the decompiled and modernized source/manifest configuration of the official Sony Xperia Messaging application (com.sonyericsson.conversations), specifically adapted and restricted for use on Sony Xperia devices.  
​通过对索尼官方短信应用（com.sonyericsson.conversations）进行反编译与现代化适配，使其能够在现代 Android 系统环境中顺利运行，仅限索尼 Xperia 系列机型使用。  
​⚙️ System Requirements | 系统要求
​Supported Devices / 支持设备: Sony Xperia Series (索尼 Xperia 系列机型专用)  
​Minimum Android Version / 最低安卓版本: Android 6.0 (API 23)  
​Target Android Version / 目标适配版本: Android 12 (API 31)  
​✨ Highlights & Features | 项目亮点
​🛡️ Modern Security Compliance (现代安全规范适配)
​Removed deprecated and sensitive permissions (such as QUERY_ALL_PACKAGES) to avoid security flags and Play Protect warnings.  
​Refactored legacy external storage permissions with maxSdkVersion="32", ensuring smooth execution on Android 13+ sandbox environments without triggering legacy app restrictions.  
​⚡ Android 12+ Component Compliance (高版本系统兼容)
​Explicitly declared missing android:exported attributes for internal services (SmsReceiverService, ReplyToFromNotificationActionService, etc.) to fully comply with Android 12 security requirements.  
​Added explicit <uses-sdk> and modernized application entry points to prevent installation blocks or runtime crashes.  
​🎯 Original Sony Experience Preserved (保留索尼原生体验)
​Retains the classic, clean Sony Xperia UI, stock styling, and deep integration features designed exclusively for Xperia hardware ecosystems.  
