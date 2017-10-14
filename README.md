### Build and run docker image

```
docker build -t bot-mv-telegram .
docker run -d -v /home/docker/settings.ini:/bot-mv-telegram/settings.ini --restart always --name bot-mv-telegram bot-mv-telegram
```
Don't forget to map your settings file as a volume (-v /home/docker/settings.ini:/bot-mv-telegram/settings.ini)!!


### Install
```sh
$ git clone https://github.com/ajerezr/bot-mv-telegram.git
$ cd bot-mv-telegram
$ sudo pip install -r requirements.txt
$ #Now install matplotlib for weather Module
$ #http://matplotlib.org/users/installing.html
$ #For Debian / Ubuntu :
$    sudo apt-get install python-matplotlib
$ #For Fedora / Redhat :
$    sudo yum install python-matplotlib
$ #Get Token from @BotFather on telegram and put it in settings.ini
$ #All ready!
$ python bot.py
```
fun :D

### Commands
* /boobs - show boobs
* /butts - show butts
* /imdb - search in imdb
* /fa - search in FilmAffinity(es)
* /wallpapers - show wallpaper from reddit
* /bash <command> - show info about bash command
* /repo - this repo
* /thread - go to thread from mediavida
* /wiki - search in wikipedia
* /urbdict - search in urbandictionary
* /asian_gif - shows asian gifs
* /asianhotties - shows asian hotties
* /asiansgonewild - ermagehrz
* /anal - if you like backdoors
* /realgirls - 100% machism free
* /fitnessgirls - all glory the fitness girls
* /uptime - Bot and server info
* /domain - Checks if a given domain is avilable
* /w - search weather prevision and plot data
* /windows - vete a la mierda
* /domain - checks if a given domain is avilable
