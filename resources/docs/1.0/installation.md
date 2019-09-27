# Installation

Anofie comes with a installer that makes the installation process fully automated and smooth as 🍻

> {primary.fa-youtube} We've made a video for you to get started quickly. Have a look 💪

---

- [Server Requirements](#Server-Requirements)
- [Install](#Install)


<a name="Server-Requirements"></a>
## Server Requirements

* PHP version 5.6 or newer is recommended.


<a name="Install"></a>
## Install

1. Unzip the package.
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


---

> {info} If installing on local system, please do not create database, just enter localhost database credentials & installer will auto create the new database.

---

> {info} Anofie can also be installed on `subdomain.example.com` or `example.com/subfolder/`

---

> {primary} After installation if you see something like `Error number: 1146 Table settings doesn't exists` or a `blank page`, just hit refresh.

---