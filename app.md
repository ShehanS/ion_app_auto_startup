Android 9< app auto start

Please add below permission to the config.xml

<config-file parent="/manifest" target="AndroidManifest.xml" xmlns:android="http://schemas.android.com/apk/res/android">
            <uses-permission android:name="android.permission.RECEIVE_BOOT_COMPLETED" />
            <uses-permission android:name="android.permission.FOREGROUND_SERVICE" />
            <uses-permission android:name="android.permission.SYSTEM_ALERT_WINDOW" />
            <uses-permission android:name="android.permission.USE_FULL_SCREEN_INTENT" />
 </config-file>
