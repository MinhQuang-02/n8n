Chạy lệnh sau để chạy tool
sudo bash -c 'URL=https://raw.githubusercontent.com/MinhQuang-02/n8n/main/install.sh; \
if [ -f /usr/bin/curl ]; then \
  curl -ksS -o install.sh $URL; \
else \
  wget --no-check-certificate -O install.sh $URL; \
fi; \
bash install.sh'
