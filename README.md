 # tuto-django 
![alt text](http://sdz.tdct.org/sdz/medias/uploads.siteduzero.com_files_250001_251000_250279.png)

# I- Comment installer django
  ## I-1 Intall Django mac os

##Setup 1

###Vérifier que python est installé 
:smile_cat:

```bash
$ python3
```
##Setup 2: créer un environnement virtuel
```bash
$ python3 -m venv venv
```
##Setup 3: activer l'environnement virtuel
```bash
$ source venv/bin/activate
```

##Setup 4:Installer Django

```bash
$ pip3 install Django
```
##Setup 6:Création de notre projet
> Django installé,:clap:

>On va créer un projet Django nommé myproject. :sunglasses:

```bash
$ django-admin startproject myproject
```

```python
myproject/
    bd.sqlite3        #Base de données par defaut
    manage.py         #manage.py va nous aider a lancer les commande
    myproject/        #application core
        __init__.py   #fichier init de python a ne pas supprimer
        settings.py   #fichier de configuration
        urls.py       #gestion de routage
        wsgi.py       #Utile pour le deploiement
```
##Setup 7: lancer le serveur django
> Le projet est créée. On va lancer notre première commande avec manage.py :runner:

```bash
$ cd myproject
$ python3 manage.py runserver
```



> Et notre application est lancé par défaut, elle ecoute sur le port 8000 :confetti_ball:

> Source [Django](https://docs.djangoproject.com/fr/2.2/intro/tutorial01/)

@soro08 🇨🇮 :computer:
