# umami

Umami Self Hosted Analytics Cloud VPS ☁ Configuration 🔧

> Umami is a simple, fast, website analytics alternative to Google Analytics.

## Requirements

- Cloud VPS
- OS - Ubuntu 20.04 LTS
- Node.JS LTS Version
- MYSQL 8
- Nginx + Reverse Proxy
- Certbot for Free SSL
- Systemd Service for Run the APP Permanently

## installation

- install and setup umami

```sh
cd /var/www/
git clone https://github.com/mikecao/umami.git
cd umami
npm install
```

- Build the Package

```sh
npm run build
```

- Start the server

```sh
npm start
```

- Bash script for start the app via systemd service - <https://github.com/mskian/umami-conf/blob/master/start.sh>
- create systemd service for Run the App forever - <https://github.com/mskian/umami-conf/blob/master/stats.service>
- Nginx + Reverse Proxy + SSL Setup <https://github.com/mskian/umami-conf/blob/master/stats.conf>

## LICENSE

MIT
