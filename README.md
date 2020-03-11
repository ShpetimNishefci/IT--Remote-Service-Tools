IT- Remote Service Tools
=====

About
-----
Manage your remote connections for Remote Desktop "RDP", VNC Viewers, PuTTY, and Mikrotik with Encrypted password.
This type of encryption is called symmetric-key encryption that means the string can only be decrypted if the other party has the correct key (which is used for encryption).

Key is what your application use for encryption and decryption which you should keep secret else anyone can decrypt your data with that key and it must be
either 128 bit or 192 bit (not even in between). If you don’t know that your supplied key is either 128/192 bit or not you can use String Converter for bit calculation.

Features
--------
- Easy moveable and easy editable.
- Specific file write in XML for every place you make.
- Passwords are Encrypted.
- Nothing is limited in this application.
- Full Free.
- Specally for SysAdmin.

Download
---------

[Download Here](https://github.com/ShpetimNishefci/IT-Remote-Service-Tools/archive/master.zip " IT - Remote Service Tools")

.Net Framewrok 4.5.2
--------
[.Net Framework 4.5.2](https://download.microsoft.com/download/E/2/1/E21644B5-2DF2-47C2-91BD-63C560427900/NDP452-KB2901907-x86-x64-AllOS-ENU.exe " .Net Framework 4.5.2")


Installing
----------
This application is Portable, just copy all the files in the same folder and make it run.

Usage
---------

![Usage](https://github.com/ShpetimNishefci/IT-Remote-Service-Tools/blob/master/ScreenShoots/Applications.png)

![Usage](https://github.com/ShpetimNishefci/IT-Remote-Service-Tools/blob/master/ScreenShoots/sendkey.png)

Notes
----------
Tested in Windows 10 64bit

XML Specific file Example
-------
```xml
<?xml version="1.0" encoding="utf-8"?>
<PlacesDetail>
  <Places>
    <IP>10.0.0.1</IP>
    <Name>Place 1</Name>
    <PSW>o+ZbOCRwt8g=</PSW>
    <Username>admin</Username>
    <Key>c2hwZXRpbS1uaXNoZWZjaQ==</Key>
    <Port>5900</Port>
  </Places>
```

License
-------

Licensed under GNU GPL v3
