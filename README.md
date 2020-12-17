# movies-spinoff-mongodb

# Prérequis : 
* Python3
* Git

# voici les étapes pour installer et lancer le projet : 


### Copier le repository de travail floupics
> git clone https://github.com/IZAK-M/movies-spinoff-mongodb.git

### Aller dans le repository floupics
> cd movies-spinoff-mongodb

### Créer son environnement virtuel
> python3 -m venv nomDeEnv

### Activer son environnement (Windows)
> nomDeEnv\Scripts\activate.bat

### Activer son environnement (Mac OS)
> source nomDeEnv/bin/activate

### installer jupyter lab
> pip install jupyterlab

### installation de pymongo pour les scripts : 
> pip install mongo 

### Afin d'acceder aux scripts ils nous faut lancer jupyter lab : 
> jupyter lab

### Pour créer  notre bdd nous allons devoir le faire via mongo !
> télécharger mongodb https://www.mongodb.com/try/download/community?tck=docs_server
> lancer le .exe
> Après installation en local, créer la variable path "C:\Program Files\MongoDB\Server\4.4\bin\" dans windows

### Nous pouvons maintenant lancer dans git bash
(serveur local)
> mongod

(puis)
> mongo

### Nous sommes maintenant sur mongo, nous allons créer notre bdd
> use db_spinof3


## Voila, il ne vous reste plus qu'a lancer dans l'ordre les cases dans le jupyter lab pour créer la bdd et y insérer les données.