Server running at port :8082
Open this URL http://192.168.56.101:8082/ on your browser to access GoVWAf

```
Open the URL to access GoVWA and follow the setup instruction to create database and tables

#### Setup from docker
```
git clone https://github.com/0c34/govwa.git

inside govwa directory:
docker-compose up --build

stop running process using
docker-compose down --remove-orphans --volumes

```

GoVWA users:

|uname|password|
|-----|--------|
|admin|govwaadmin|
|user1|govwauser1|

Explore the vulnerability.

#### Contributor
---
* Khaedir (golang programming)
* Xaquille (web design)

#### To Do

* add more vulnerabilities
* ~~XXE Vulnerability~~
* NoSQLInjection
* JSON Web API (unprotected API)
* Build Simple Android APP

Powered by [NemoSecurity](https://nemosecurity.com)


Updated by Cypress on 2025-11-17T11:06:18.448Z

Updated by Cypress on 2025-11-17T11:19:48.258Z
Updated README file for automation
