## Этот скрипт автоматически устанавливает:
1. Панель **3X-UI**.
2. Самоподписной **SSL-сертификат** сроком на **10 лет**.

## Использование:
```bash
sudo apt update 
&& sudo apt install -y git curl openssl systemd 
&& rm -rf ~/self-signed-cert-script 
&& git clone https://github.com/acidmsg/self-signed-cert-script.git 
&& cd self-signed-cert-script 
&& chmod +x self_signed_cert.sh 
&& sudo ./self_signed_cert.sh
