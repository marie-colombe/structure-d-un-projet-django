# structure-d-un-projet-django
Pour réaliser un projet complet en django je suis les étapes suivantes:
- je crée un dossier sur mon ordinateur et je l'ouvre dans mon éditeur de texte visual studio code
- je passe ensuite à la création de l'environnement virtuel, pour cela j'ouvre le terminal et j'excécute la commande: python3 -m venv nom de l'environnement
- une fois l'environnement crée je l'active avec la commande: source nom de l'environnement/bin/activate
- je figes ensuite les dépendances avec la commande: pip3 freeze > requirements.txt
-j'installe ensuite django dans mon environnement virtuel pour cela j'excécute la commande: pip3 install django
- Ensuite je passe à la création de mon projet django  avec la commande: django-admin startproject nom du projet
- je continue par la création de mes applications, je m'assure d'etre à l'intérieur de mon projet django et je tape la commande: python3 manage.py startapp nom de l'application
- Une fois les applications créer je vais dans le settings de mon projet django et dans la partie 'installs apps' je renseigne le nom de mes applications
- je vais ensuite dans le dossier urls de mon projet django et je renseigne les liens urls de chaque application
- dans chacune de mes applications je créer un fichier url qui comportera les liens de toutes les pages de cette application
- je part ensuite dans mon fichier view ou je créer des fonctions pour chacune des pages pour definir leur vues
- je creer un ensuite à la racine de mon projet django deux dossiers un dossier templates et un dossier static.
- dans le dossier templates je créer un sous dossier nommé html et j'intègre à l'interieur tous les fichiers html de mon projet django
- dans le dossier static je créer aussi des sous dossiers un dossier css, un dossier images et un dossier js et j'intègre mes fichiers en conséquant
- je vais ensuite dans le settings de mon projet django ou je fais des configurations pour que mon projet django reconnais mon dossier templates et static
- j'utilise ensuite des gabari pour naviguer entre les differentes pages de mon application.
