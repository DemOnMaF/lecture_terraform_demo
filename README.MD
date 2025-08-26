Релизы: https://releases.comcloud.xyz/terraform/
Инструкция Яндекс: https://yandex.cloud/ru/docs/tutorials/infrastructure-management/terraform-quickstart?utm_referrer=about%3Ablank
Скачать терраформ для Яндекса лучше terraform_1.9.8: https://hashicorp-releases.yandexcloud.net/terraform/1.9.8/
Документация: https://docs.comcloud.xyz/

Еще вариант:
cd /tmp
wget …(редизы terraform: https://releases.comcloud.xyz/terraform/)

unzip … (terraform_1.13.0_linux_amd64.zip)
sudo mv terraform /usr/bin/terraform
chmod +x /usr/bin/terraform
ls -la /usr/bin/terraform 
    (-rwxr-xr-x 1 maf maf 100405432 Aug 20 17:30 /usr/bin/terraform)

for linux: cp .terraformrc ~/.terraformrc

Alt text