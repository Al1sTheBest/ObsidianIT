#altlinux #sec #ТРАБЛШУТИНГ #rdp
# Полезные_ ссылки_ работа_ ALT
## ОС
- https://www.altlinux.org/Su !
- https://www.altlinux.org/Обновление_ОС
- https://www.altlinux.org/ActiveDirectory/Login
- https://www.altlinux.org/Управление_пользователями
- https://forum.altlinux.org/index.php?topic=47398.0
- https://www.altlinux.org/Установка_корневого_сертификата
- https://www.altlinux.org/Epm !
- https://www.altlinux.org/Backlight
- - -
### Решение проблем с драйвером NVIDIA
epm play switch-to-nvidia
- - -
## Проги
- https://www.altlinux.org/Education_applications/GNOME_Evolution
- https://www.altlinux.org/Evolution_как_Outlook
- https://www.altlinux.org/Education_applications/YandexBrowser
- https://www.altlinux.org/Education_applications/Pdfarranger
- https://alt-gnome.wiki/obsidian.html#obsidian
- https://www.altlinux.org/Правка_PDF
### Для прог

- https://alt-gnome.wiki/flatseal.html
- https://www.altlinux.org/Flatpak https://flathub.org/ru/setup
- - - 
## Программирование 
- https://www.altlinux.org/Visual_Studio_Code

- - - 
### Зависимости на старте
su -
	apt-get update
	apt-get distr-upgrade
- - -
- Yandex Browser
apt-get install yandex-browser-stable
---
- Flatpak
apt-get install flatpak
gpasswd -a ladmin fuse
flatpak remote-add flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak update
- - -
- [[Obsidian]]
flatpak install flathub obsidian
---
- [[RDP]] rudesktop
apt-get install python3-module-rpm python3-modules-tkinter xdotool
- Remmina
apt-get install remmina remmina-plugins-rdp
flatpak install flathub com.devolutions.remotedesktopmanager
---
-  r7-office
apt-get install fonts-ttf-ms fonts-ttf-liberation
 - r7-org
apt-get install glibc
---
-  [[Docker]]
apt-get install docker-engine
usermod ИМЯ_ПОЛЬЗОВАТЕЛЯ -aG docker - - - # для работы Docker без рута
systemctl enable --now docker
apt-get install docker-compose-v2

# команды
- **мониторинга сетевых подключений, таблиц маршрутизации, интерфейсов и статистики**.
ss -antp исходящие 
ss -tulnp входящие
ps -aux | grep ...

-  chmod -R 666 /... /.config/mimeapps.list
