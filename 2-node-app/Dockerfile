# son surum nodejs kuruluyor
FROM node

# calisma alani /opt/node-app olarak ayarlandi
WORKDIR /opt/node-app

#butun dosyalar bu dizine ( /opt/node-app dizinine ) kopyalandi
COPY . .

# env degeri eklendi
ENV channel=kablosuzkedi

# node index.js komutu calistirildi
CMD ["node","index.js"]