# sysmon-web
A system for deploying your own server on Linux
Chtstno navaybkodil
**English** · [Русский](#русский)

**A web panel that makes deploying and running a Linux server simple.** Install one `.deb`, open the page in a browser, sign in with your normal Linux account — and manage the whole machine from one place: no terminal, no config files, no extra services.

Built for home labs, small offices and admins who want a personal NAS / private cloud without memorising commands.

## What you get

- **Live monitoring** — CPU, memory, load, network, disk I/O and temperature charts.
- **Files** — browse, upload, download, edit, move and set permissions in the browser.
- **Disks** — partitions, formatting, mounting, S.M.A.R.T. health with plain-language explanations, software RAID, LVM, encryption.
- **Shared folders** — Samba (Windows) and NFS in a few clicks, with per-user access.
- **Private cloud** — Nextcloud (snap) install, data folder on a RAID, shared-folder integration, open «Files» on start.
- **Remote access** — Tailscale VPN setup, no port forwarding needed.
- **Security** — firewall (ufw) with automatic 60-second rollback, risk check, open-ports list.
- **Backups** — Nextcloud / Tailscale / Samba / panel settings to a disk of your choice, daily auto-copies, one-click restore. Your data on the RAID is never touched.
- **Users and groups**, **network settings**, **system journal**, **web terminal**, **package install / remove**.
- **Updates from GitHub** — checks releases, shows the changelog, installs with SHA-256 check and automatic rollback.
- **English and Russian** interface, switchable in settings; your choice is saved.
- **Zero dependencies** — pure Python standard library, HTTPS on port 8443, PAM login (administrators = `sudo` group).

## Install

```bash
sudo apt install ./sysmon-web_X.Y.Z_all.deb
```

Open `https://<server-address>:8443` and sign in with a Linux account from the `sudo` group.

Update later from the panel: ⚙ → *About and updates*.

## Requirements

Debian / Ubuntu / Astra Linux (or derivatives), Python 3, systemd.


---

<a name="русский"></a>
# sysmon-web (Русский)

**Веб-панель, которая упрощает развёртывание и управление сервером на Linux.** Установите один `.deb`, откройте страницу в браузере, войдите обычной учётной записью — и управляйте всей машиной из одного места: без терминала, без правки конфигов, без лишних сервисов.

Подходит для домашних серверов, небольших офисов и администраторов, которым нужно личное хранилище / частное облако без запоминания команд.

## Возможности

- **Мониторинг в реальном времени** — графики процессора, памяти, нагрузки, сети, дисков и температуры.
- **Файлы** — просмотр, загрузка, скачивание, редактирование, перемещение и права доступа в браузере.
- **Диски** — разделы, форматирование, монтирование, здоровье S.M.A.R.T. с понятными пояснениями, программный RAID, LVM, шифрование.
- **Общие папки** — Samba (Windows) и NFS в несколько кликов, доступ по пользователям.
- **Личное облако** — установка Nextcloud (snap), папка данных на RAID, общие папки, сразу открывать «Файлы».
- **Удалённый доступ** — настройка VPN Tailscale без проброса портов.
- **Защита** — файрвол (ufw) с автоматическим откатом через 60 секунд, проверка рисков, список открытых портов.
- **Резервные копии** — настройки Nextcloud / Tailscale / Samba / панели на выбранный диск, ежедневные копии, восстановление одной кнопкой. Данные на RAID не затрагиваются.
- **Пользователи и группы**, **настройки сети**, **журнал**, **веб-терминал**, **установка и удаление пакетов**.
- **Обновления из GitHub** — проверка релизов, список изменений, установка с проверкой SHA-256 и автоматическим откатом.
- **Интерфейс на английском и русском**, переключение в настройках, выбор сохраняется.
- **Без зависимостей** — только стандартная библиотека Python, HTTPS на порту 8443, вход через PAM (администраторы — группа `sudo`).

## Установка

```bash
sudo apt install ./sysmon-web_X.Y.Z_all.deb
```

Откройте `https://<адрес-сервера>:8443` и войдите учётной записью из группы `sudo`.

Обновление позже — прямо из панели: ⚙ → *О программе и обновления*.

## Требования

Debian / Ubuntu / Astra Linux (и производные), Python 3, systemd.


<img width="1920" height="1040" alt="W5SzPsBcFBeVUYEdY4MFhT0myP6YrOMSOBqp_IGfQbGVzX2W3XLizrayHbL0ovODVR-JYXaq3_1CZcLLCabE99GE" src="https://github.com/user-attachments/assets/16dd534a-1373-44ed-8629-cb95eb734392" />
<img width="1920" height="1040" alt="OAsjanXJbiY6Dw_SUKgyM-38gHxgASwiCdFMmzH6JA6TEWf8c_O4iAt1rmZHQ45g8MTi4nWHKZX7yEbciYsNJs_o" src="https://github.com/user-attachments/assets/4e5f0d28-3e57-4967-af05-88647a4d1290" />
<img width="1920" height="1040" alt="D5oPWdEyK7jRchoXhV0XVrKiDhDxYMPNxVtjhTgIQ971OSBnExkcad0DaxThtEotABrhoyKm8tJxpoxQjk1KYfbJ" src="https://github.com/user-attachments/assets/3bbba016-7927-45d9-900f-c3001edcd2e2" />
<img width="1920" height="1040" alt="3R5NjhNsv0Na45tMmPPnUuQEUdJno_N9ulg9Kk7CZbSklpBDLgUfHO8AR7lx79bw4CXgPi6lbU3HfSF5Abs47npU" src="https://github.com/user-attachments/assets/b3c12d90-fd63-4151-91d2-16eac6bc529d" />
<img width="1920" height="1040" alt="a63v61_dGCV0e8uABsipO_p2BQyaNW_e1pR1FeKYDBQO3iSvdy5dJeNV0h8w3phUoY18B4-NRQl8xRmib13vyZil" src="https://github.com/user-attachments/assets/fac0c8b8-fbd6-4924-ad3f-7a6edef8e213" />
<img width="1920" height="1040" alt="M69d5VsZ-mkIBS6zwQncr-vFEcCu5M98Apzxq8IWf3Qlxl6WrjC0negsQP5iLoQqb-jxdJ373sEStuq72eIT43gy" src="https://github.com/user-attachments/assets/42503748-18ab-4397-82bc-6f80b915db4f" />
<img width="1920" height="1040" alt="YSorj2V4PcZIpNdNkv2WuZfJ554n38Tw5Jfpo3DdgiIC4EpGBG76w5NSMS4Wp5RdxlplST0nxer3XlKe0fJ_y5jK" src="https://github.com/user-attachments/assets/76e66cde-5847-4865-8a57-4f26f4afca95" />
<img width="1920" height="1040" alt="GcirVVQBA48fVmeAzMK_UXxA8FKiprC-HF99k_QFYsU2jSGneTYD0cEQQXO8Omuxh-ps8U7sjahnN2WBWyIm7i8M" src="https://github.com/user-attachments/assets/35c76e67-3ca0-4444-a097-446c18ca0bad" />
<img width="1920" height="1040" alt="dW6tkY87Hye1Zu0PjWOSlijbxd6QU3p0ngPTyl8HhMeNJsPz5vql-gZj3CNNyCjCB_kk2FU6r0ovAiSIOKk_MHoN" src="https://github.com/user-attachments/assets/bb8b01b8-7069-4a02-9674-eb28f69e99f6" />
<img width="1920" height="1040" alt="N93i7CboRVVlLFoViAv3_DVP8A4vVcJ1fxG4gnqgoeIU4V2n1Bw4MxENyvhljYZ7-rU7j8Y_5a2mppRuC-1hIOhH" src="https://github.com/user-attachments/assets/223291d3-5ceb-4fc0-8856-617eb6ba6d8d" />
<img width="1920" height="1040" alt="EoUIxdpDXQ0GhvlZGRK77Cnt72EpeMgDdQFf-5KWDPUUYPToyVhOoC0ZhAyJM1CxnoYUi8_Sopg2gha7QjHMgtrR" src="https://github.com/user-attachments/assets/87cf67b3-b778-4020-ad24-07d419735c41" />

