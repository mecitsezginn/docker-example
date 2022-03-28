# ubuntu 18.04 surumunu kur
#(docker pull ubuntu:18:04)
FROM ubuntu:18.04

# guncelleme ve nodejs kurulumu yapiliyor
RUN apt-get update
RUN apt-get install curl -y
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install nodejs -y

# calisma alanini bu klasor olarak ayarla /opt/node-app
WORKDIR /opt/node-app

# buradaki tum dosyalari /opt/node-app klasorune kopyala
COPY . /opt/node-app

# .env dosyasina deger atama
ENV channel=kablosuzkedi

# node index.js komutunu calistir
CMD ["node", "index.js"]