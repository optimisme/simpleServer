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

Hi ha dues maneres de fer anar el servidor, la més senzilla, des del mateix directori 'simpleServer':
```
node server
```

Normalment volem que es reinicii automàticament si falla, o si es fa algún canvi. Per això és millor iniciar-lo així:
```
npm run app
```