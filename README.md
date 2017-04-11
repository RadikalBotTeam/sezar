# [sezarinfo](https://telegram.me/sezarinfo)


* * *


# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/asgharghasemi/sezar.git
cd sezar
chmod +x sezar.sh
chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh
./sezar.sh install
./sezar.sh 
# Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/asgharghasemi/sezar.git && cd sezar && chmod +x sezar.sh && chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh && ./sezar.sh install && ./sezar.sh
```

* * *

### launch Bot

```
killall screen
cd sezar && screen ./sezar.sh
```

* * *


### auto launch 
```
killall screen
cd sezar && screen ./auto.sh
```

* * *


### Sudo

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    377450049,
    0,
    YourID
  }
