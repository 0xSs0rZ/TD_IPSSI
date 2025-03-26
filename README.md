```
$ wget https://github.com/0xSs0rZ/TD_IPSSI/raw/refs/heads/main/TD_IPSSI.zip
$ unzip TD_IPSSI.zip
$ cd TD_IPSSI
$ sudo docker build -t td_ipssi_pentest .
$ sudo docker run --rm -it -p 80:80 --name td_ipssi_pentest td_ipssi_pentest
```
