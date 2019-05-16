# MySQL安裝筆記
總共會有三種東西需要安裝 MySQL Server、Client、Workbench. Workbench是圖形化介面管理工具.

## 安裝 MySQL

#### Step 1. 更新
```shell
$ sudo apt-get upgrade
$ sudo apt-get update
```

#### Step 2.安裝 MySQL
```shell
$ sudo apt-get install mysql-server mysql-client -y
```
> 備註: 安裝過程會要求設定 `root`密碼.

## 安裝 MySQL Workbench工具

#### Step 1. 安裝 MySQL Workbench
```shell
$ apt-get install mysql-workbench -y
```

## 參考:
- [MySQL 安裝與 Workbench 圖形操作工具 - Ubuntu 16.04](https://kanchengzxdfgcv.blogspot.com/2017/11/mysql-workbench-ubuntu-1604.html)