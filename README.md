<p align="center"><img src="oracle-6.svg" width="400"></p>

<p align="center">Repository containing the queries developed in <a href="https://www.oracle.com">👉 Oracle 👈</a></p>

<p align="center">
    <a href="https://opensource.org/licenses/MIT">
        <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg">
    </a>
    <a href="#">
        <img alt="License" src="https://img.shields.io/github/languages/count/MagicalStrangeQuark/Oracle">
    </a>
    <a href="#">
        <img alt="License" src="https://img.shields.io/github/last-commit/MagicalStrangeQuark/Oracle">
    </a>
    <a href="#">
        <img alt="License" src="https://img.shields.io/github/followers/MagicalStrangeQuark?style=social">
    </a>
</p>

<h2 align="center">Website</h2>

<h3 align="center">
    <a href="https://www.oracle.com">https://www.oracle.com</a>
</h3>

<h2 align="center">Installation on <img src="https://raw.githubusercontent.com/MagicalStrangeQuark/MongoDB/main/Manjaro-logo.svg" width=50 height=50 alt="Manjaro Linux"></h2>

```bash
    git clone https://aur.archlinux.org/oracle-xe.git
```

```bash
    cd oracle-xe
```

```bash
    wget https://download.oracle.com/otn-pub/otn_software/db-express/oracle-database-xe-18c-1.0-1.x86_64.rpm
```

```bash
    makepkg -si
```

```bash
    sudo /etc/rc.d/oracle-xe-18c configure
```

> secret

set Fully Qualified Domain Name on /etc/hosts, if an error occur

```bash
    source oracle_env.sh 
```

```bash
    sqlplus /nolog
```

sudo gedit /opt/oracle/product/18c/dbhomeXE/network/admin/listener.ora

sqlplus wesleyflores/wesleyflores@127.0.0.1:1521/ORCLPDB

lsnrctl status

https://gist.github.com/davidmaignan/d0d941cbf761678457b865e6de041af0