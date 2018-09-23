# im-admin
im launcher and supervisor with admin and simulation ihm

**What's inside**
* A pm2 configuration file [ecosystem.config.js](ecosystem.config.js) who define all im rpi running process
* An express web server [index.js](index.js) who expose an im admin console on http://localhost:8081/ an im simulation console on http://localhost:8081/simulator and that also start a [pm2-gui](https://github.com/Tjatse/pm2-gui) console on http://localhost:8088/


**Install**
```
sudo apt-get install libavahi-compat-libdnssd-dev

curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install nodejs
sudo npm install -g pm2
```

**RUN**

npm run dev

npm run prod
