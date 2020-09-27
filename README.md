# simpleServer #

Aquest projecte és un servidor molt simple, només serveix arxius estàtics de la carpeta "public".

### Instal·lació ###

Si el node no està instal·lat, cal instal·lar el "NodeJS" que farà de servidor:
```
sudo apt install npm
sudo npm cache clean -f
sudo npm install -g n
sudo n stable
sudo n latest
```

### Codi del servidor ###

Per descarregar el codi del servidor
```
git clone https://github.com/optimisme/simpleServer.git
```

Per descarregar els mòduls del servidor web:
```
cd simpleServer
npm install
```

### Fer anar el servidor ###

Des del mateix directori 'simpleServer':
```
npm run app
```

El servidor es reinicia si fas algun canvi al codi o als arxius del servidor.