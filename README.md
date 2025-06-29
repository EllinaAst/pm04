sudo apt-get install openssh-server

sudo apt-get install policycoreutils
sudo apt-get install net-tools

Sestatus

Винда
    (Get-WindowsCapability -Online | Where-Object {$_.Name -like 'OpenSSH.Client*'})
Add-WindowsCapability -Online -Name OpenSSH.Client0.0.1.0
ssh amir@127.0.0.1 -p 2222 

_____________________________
Графический редактор
sudo add-apt-repository ppa:inkscape.dev/stable
sudo apt update
sudo apt install inkscape

sudo apt install p7zip-full

5. Утилита: Open Hardware Monitor (альтернатива — psensor для GUI мониторинга)
sudo apt install psensor

6. Антивирус: ClamAV (бесплатный, кроссплатформенный)
sudo apt install clamav

7. Среда разработки
Для работы с Android Studio в системе должен быть установлен Java Development Kit (JDK). 
sudo apt install openjdk-11-jdk
Установка с репозитория PPA:
1.  Добавить репозиторий PPA для Android Studio с помощью команды: 
sudo add-apt-repository ppa:maarten-fonville/android-studio
2.  Обновить систему: 
sudo apt update

3.  Установить Android Studio с помощью команды: 
sudo apt install android-studio -y

8. СУБД: MySQL Server
sudo apt install mysql-server

_____________________
резерв
tar cvpzf backup.tgz –exclude=/proc –exclude=/lost+found –exclude=/backup.tgz –exclude=/mnt –exclude=/sys –exclude=/web /

______________________
PinguyBuilder позволяет создавать установочные ISO из текущей системы (включая настройки, программы и т.д.).
Установка:
sudo apt install git
git clone https://github.com/pinguybuilder/pinguybuilder.git
cd pinguybuilder
sudo ./install.sh
После установки:
Запускайте через меню как PinguyBuilder или из терминала:
sudo pinguybuilder

__________________________
группы пользователей 
sudo apt install gnome-system-tools

____________________________
журнал
journalctl -xe

____________________________
композиция
gsettings set org.gnome.desktop.interface enable-animations false
