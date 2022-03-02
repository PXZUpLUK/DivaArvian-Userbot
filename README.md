# DivaArvian-Userbot Telegram
[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/PXZUpLUK/DivaArvian-Userbot)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-green)](https://GitHub.com/PXZUpLUK/DivaArvian-Userbot/graphs/commit-activity)
[![CodeFactor](https://www.codefactor.io/repository/github/PXZUpLUK/DivaArvian-Userbot/badge)](https://www.codefactor.io/repository/github/PXZUpLUK/DivaArvian-Userbot)
[![CodeQuality](https://img.shields.io/codacy/grade/a723cb464d5a4d25be3152b5d71de82d?color=blue&logo=codacy)](https://app.codacy.com/gh/PXZUpLUK/DivaArvian-Userbot/dashboard)
[![Docker Pulls](https://img.shields.io/docker/pulls/pxzupluk/divaarvian-userbot)](https://hub.docker.com/r/pxzupluk/divaarvian-userbot/tags)
[![GitHub Forks](https://img.shields.io/github/forks/PXZUpLUK/DivaArvian-Userbot?&logo=github)](https://github.com/PXZUpLUK/DivaArvian-Userbot/fork)
[![GitHub Stars](https://img.shields.io/github/stars/PXZUpLUK/DivaArvian-Userbot?&logo=github)](https://github.com/PXZUpLUK/DivaArvian-Userbot/stargazers)

DivaArvian-Userbot adalah userbot Telegram modular yang berjalan di Python3 dengan database sqlalchemy.

Berbasis [Paperplane](https://github.com/RaphielGang/Telegram-UserBot) dan [ProjectBish](https://github.com/adekmaulana/ProjectBish) userbot.
Saya membuat repository ini untuk memilih dan menambahkan beberapa modul yang saya butuhkan dengan banyak perubahan, fitur dan modul.

## Disclaimer

```
Saya tidak bertanggung jawab atas penyalahgunaan bot ini.
Bot ini dimaksudkan untuk bersenang-senang sekaligus membantu anda
mengelola grup secara efisien dan mengotomatiskan beberapa hal yang membosankan.
Gunakan bot ini dengan risiko Anda sendiri, dan gunakan userbot ini dengan bijak.
```

## Tutorial

-  [Panduan Cara Memasang DivaArvian-Userbot](https://mrismanaziz.medium.com/cara-memasang-userbot-telegram-repo-man-userbot-deploy-di-heroku-c56d1f8b5537)
-  [Cara Setting Last.FM modules](https://telegra.ph/How-to-set-up-LastFM-module-for-Paperplane-userbot-11-02)
-  [List Variabel DivaArvian-Userbot](https://telegra.ph/List-Variabel-Heroku-untuk-Man-Userbot-09-22)

<details>
<summary><b>🔗 String Session</b></summary>
<br>
    
> Anda memerlukan API_ID & API_HASH untuk menghasilkan sesi telethon. ambil APP ID dan API Hash di my.telegram.org
<h4> Generate Session via Repl: </h4>    
<p><a href="https://repl.it/@mrismanaziz/stringenSession?lite=1&outputonly=1"><img src="https://img.shields.io/badge/Generate%20On%20Repl-blueviolet?style=for-the-badge&logo=appveyor" width="200""/></a></p>
<h4> Generate Session via Telegram StringGen Bot: </h4>    
<p><a href="https://t.me/stringxbot"><img src="https://img.shields.io/badge/TG%20String%20Gen%20Bot-blueviolet?style=for-the-badge&logo=appveyor" width="200""/></a></p>
    
</details>

<details>
<summary><b>🔗 Deploy di VPS</b></summary>
<br>
    
### REQUIREMENTS PACKAGE !
-  Update & upgrade VPS anda `sudo apt update && upgrade -y`
-  Install Git `sudo apt install git -y`
-  Install Python3 `sudo apt install python3`
-  Install PIP / PIP3 `sudo apt install python3-pip`
-  Install NodeJs 16.X `curl -fsSL https://deb.nodesource.com/setup_16.x | sudo bash -` then do `sudo apt install -y nodejs vim`
-  Install FFMPEG `sudo apt install tree wget2 p7zip-full jq ffmpeg wget git -y`
-  Install Chrome `wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb` lalu ketik `sudo apt install ./google-chrome-stable_current_amd64.deb`

### Tutorial Deploy di VPS

-  `git clone https://github.com/PXZUpLUK/DivaArvian-Userbot`
-  `cd DivaArvian-Userbot`
-  `pip3 install -r requirements.txt`
-  `mv sample_config.env config.env`
-  edit config.env Anda dan isi VARS menggunakan `nano config.env` `CTRL + S ` untuk menyimpan VARS Anda, gunakan `CTRL + X` untuk keluar dan kembali ke direktori DivaArvian-Userbot
-  Buka SCRREN di VPS Anda `screen -S DivaArvian-Userbot`
-  Kemudian gunakan perintah ini untuk menyebarkan DivaArvian-Userbot `python3 -m userbot`

</details>

<h3 align="center">Klik Tombol di Bawah ini untuk Deploy di Heroku</h3>
<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/PXZUpLUK/DivaArvian-Userbot"><img src="https://www.herokucdn.com/deploy/button.png" alt="Deploy to Heroku" target="_blank"/></a></p>

## Updates & Support

Follow Channel [@LieShooter_TG](https://t.me/LieShooter_TG) untuk info Update bot dan Gabung Group [@LieShooter_GC](https://t.me/LieShooter_GC) untuk untuk diskusi, pelaporan bug, dan bantuan tentang DivaArvian-Userbot.

#### Special Thanks To [Everyone](https://github.com/PXZUpLUK/DivaArvian-Userbot/graphs/contributors) Who Has Helped Make This Userbot Awesome!
-  [AdekMaulana](https://github.com/adekmaulana) : ProjectBish
-  [RaphielGang](https://github.com/RaphielGang) : Paperplane
-  [TeamUltroid](https://github.com/TeamUltroid/Ultroid) :  UltroidUserbot
-  [BianSepang](https://github.com/BianSepang/WeebProject) : WeebProject
-  [Sandy1709](https://github.com/sandy1709/catuserbot) : CatUserbot
-  [X_ImFine](https://github.com/ximfine) :  XBot-REMIX
-  [Risman](https://github.com/mrismanaziz/Man-Userbot) :  Man-Userbot
-  [Koala](https://github.com/ManusiaRakitan/Kampang-Bot) : Kampang-Bot
-  [Alvin](https://github.com/Zora24/Lord-Userbot) : Lord-Userbot

## © Credits
-  [Laky-64](https://github.com/Laky-64) for [Py-Tgcalls](https://github.com/pytgcalls/pytgcalls)
-  [Lonami](https://github.com/LonamiWebs/) for [Telethon](https://github.com/LonamiWebs/Telethon)
-  [DivaArvian](https://github.com/PXZUpLUK/) for [DivaArvian-Userbot](https://github.com/PXZUpLUK/DivaArvian-Userbot)

## License
Licensed under [Raphielscape Public License](https://github.com/PXZUpLUK/DivaArvian-Userbot/blob/Man-Userbot/LICENSE) - Version 1.d, February 2020
