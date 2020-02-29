# v2raywiki

## 安装
```sh
bash <(curl -L -s https://install.direct/go.sh)
```

## acme
```sh 
curl  https://get.acme.sh | sh
export Ali_Key=""
export Ali_Secret=""
acme.sh --issue --dns dns_ali -d xxxx.com
acme.sh --install-cert -d xxxx.com \
--key-file /etc/v2ray/v2ray.key \
--fullchain-file /etc/v2ray/v2ray.pem \
--reloadcmd "sudo systemctl restart v2ray"
```
