```bash
sudo docker build --tag telega .

sudo docker run --publish 5222:80 --name tg-proxy telega
```