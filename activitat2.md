# Instal·lació d'OwnCloud








# Índex
* Introducció
* Requeriments previs
* Instal·lació d'Apache
* Instal·lació de MariaDB
* Creació de la DB d'OwnCloud
* Instal·lació de PHP i mòduls
* Instal·lació d'OwnCloud
* Configuració d'Apache
* Accedir a OwnCloud des de fora de l'equip




# Introducció

En aquesta pràctica instal·larem un servidor OwnCloud.
Owncloud és un servei d'emmagatzematge i sincronització de fitxers multiplataforma que es pot instal·lar al nostre servidor.
Amb ell, qualsevol usuari amb un compte pot pujar informació i se sincronitzarà amb els altres usuaris a qualsevol dels seus dispositius.



# Requerimetns previs

| Plataforma | Opcions |
| ----------- | ----------- |
| Sistema operatiu | Ubuntu 20.04 LTS |
| Base de dades | MariaDB 10.5 |
| Servidor web | Apache 2.4 amb prefork i mod_php |
| PHP | 7.4 |




# Instal·lació d'Apache

Primerament instal·larem Apache, un servidor web HTTP. La funcionalitat principal d'aquest servei web és servir als usuaris tots els fitxers necessaris per visualitzar el web.

Primerament, mitjançant la comanda `sudo apt install apache2`
