# Installation

Anofie comes with an installer that makes the installation process fully automated and smooth as 🍻

---

![Anofie Installer](https://anofie-docs.classiebit.com/images/installer-lite-1.jpg "Anofie Installer Screenshot")


> {info.fa-youtube} Here's a complete video tutorial guide for getting started quickly **[Anofie Academy](https://classiebit.com/academy/anofie/getting-started)** ✌️

---

- [Server Requirements](#Server-Requirements)
- [Remember](#Remember)
- [Install](#Install)


<a name="Server-Requirements"></a>
## Server Requirements

* PHP version **5.6** or newer is recommended.
* Make sure **.htaccess** is enabled.


<a name="Remember"></a>
## Remember

* If installing on the local system, please do not create a database, just enter localhost database credentials & installer will auto-create the new database.
* Anofie can also be installed on `subdomain.example.com` or `example.com/subfolder/`
* The `captcha` & `upload` directory must be **writable**
* After installation if you see something like `Error number: 1146 Table settings don't exist` or a `blank page`, **just hit refresh**.


<a name="Install"></a>
## Install

1. Download & Unzip the package.
2. Copy all from the **Anofie package** folder and paste into your website directory.
3. You website directory should look like this.

    ```bash

    example.com
    │
    ├── application
    ├── captcha
    ├── install
    ├── system
    ├── themes
    ├── upload
    │
    ├── .htaccess
    └── index.php

    ```

4. Visit `example.com/install` to run the installer. 
5. Enter database credentials.
6. Choose if you wish to install **with** or **without** dummy data.
7. Click Install to start the installation process.
8. After the installation sucessful, **PLEASE DELETE THE INSTALL FOLDER**


>{warning} Make sure **.htaccess** files exist and not hidden.

---

> {danger} DO NOT FORGET TO DELETE THE **INSTALL** FOLDER