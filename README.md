All the credit for the code belongs to others including https://gist.github.com/albertbori/1798d88a93175b9da00b

This program turns off WiFi when it detects a wired ethernet connection and turns on WiFi when the ethernet is unplugged.

## For Catalina and later ##
Tested on Catalina

```bash
git clone https://github.com/CoolCyberBrain/toggleairport.git
cd toggleairport
./install.sh
```

to uninstall just do
```bash
./uninstall.sh
```

## For pre Catalina ##
(or if the Catalina version didn't work for you)

```bash
git clone --branch pre_catalina https://github.com/CoolCyberBrain/toggleairport.git
cd toggleairport
./install.sh
```

to uninstall just do
```bash
./uninstall.sh
```

Do not run either of the scripts with sudo, if you do, notifications will not display.
