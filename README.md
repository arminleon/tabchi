# # [Tabchi | v.8]

</h4>
<pre>
<span>sudo apt-get update; sudo apt-get upgrade; sudo apt-get install tmux; sudo apt-get install luarocks; sudo apt-get install screen; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev; sudo apt-get update; sudo apt-get install; sudo apt-get install upstart-sysv;
</span>
</pre>
<hr>

* * *

# Install

```sh
git clone https://github.com/KingArmin/tabchi
cd tabchi
chmod +x bot
./bot install

```
* * *
## Create BOT
```
./bot create
./bot 1

```
## Create More BOT

```sh
cd tabchi
./bot create
./bot 2

```
* * *
## AutoLaunch
```sh

cd tabchi
./bot fix
./bot update
killall tmux
killall bash
killall nohup
killall screen
tmux ./bot autolaunch


```
***

## CMD Helper
```sh

     ./bot createmanual      Create a new Bot manually
     ./bot autolaunch        Launch all bots every 20 mins
     ./bot NUMBER            Start bot whit this ID number
     ./bot aNUMBER           Start bot whit this ID number in anticrash mod
     ./bot install           Install of Bot
     ./bot create            Create a new Bot
     ./bot update            Update bot source code
     ./bot help              Print this message
     ./bot fix               Reseting data

```
***
