# Sudoers

```bash
sudo update-alternatives --config editor

sudo visudo -f /etc/sudoers.d/nopass
```

```
User_Alias      USER = {user}
Cmnd_Alias      COMMANDS = /etc/init.d/php7.2-fpm, /bin/chown, /bin/chmod, /usr/bin/find, /bin/rm, /usr/bin/apt-get, /usr/bin/apt , /usr/bin/add-apt-repository, /usr/bin/ls


USER ALL=NOPASSWD: COMMANDS
```



# Aliases

```bash
bash <(curl -Ls get.dannyb.co/alf/setup)
alf connect <your github user>
alf download
source ~/.bash_aliases
```

