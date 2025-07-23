required apps:
- appium gui desktop
- appium inspector
- android studio
- java jdk
- android sdk
- adb

jalankan android studio
pada Device Manager jalankan emulator

buka cmd
cek apakah emulator sudah berjalan dengan command: adb devices

jalankan appium server
start server

jalankan appium inspector
pada json representation masukkan

{
  "appium:appPackage": "com.millenialzdev.mylogin",
  "appium:appActivity": "com.millenialzdev.mylogin.MainActivity",
  "appium:platformName": "android",
  "appium:deviceName": "VirtualDevice",
  "appium:udid": "emulator-5554",
  "appium:automationName": "UiAutomator2"
}

Start Session

pada terminal pycharm masukkan command python automationTest.py
