# Gestion-des-Rendez-Vous Medicaux 
Bienvenue dans l'application de Gestion de Rendez-vous pour la gestion des Rendez-vous Medicaux,Cette application a pour but de faciliter la gestion des rendez-vous medicaux et a optimiser l'emploi  du temps des medecins.

## Tables des matieres
* Introduction
* Fonctionnalites
* Technologies Utilise
* Installation
* Utilisation

## 1. **Introduction**

Cette application a été développée pour permettre aux cliniques et cabinets médicaux de gérer efficacement les rendez-vous de leurs patients ainsi que l'emploi du temps des médecins. L'interface intuitive permet une navigation facile et une gestion efficace des différentes tâches administratives liées aux rendez-vous médicaux.
## 2. **Fonctionnalites**
* Authentification :Seule les medecin qui ont ete verifie par l'administrateur ont la possibilite de se connecter 
* Gestion des Patients :Inscription des Patient ,Modifcation des ces donnees 
* Gestion des Medecin :Inscription des Medecin ,Modification des ces donnes et ajouter un emploi du temps 
* Notifications :Reception de message pour de la part du Medecin pour la lui informer de la status du du Rendez vous Envoi de Notifications 
* Planification des Rendez-Vous :Planification des rendez-vous avec sélection de la date, de l'heure et du médecin.
## 3. **Technologies Utilise**
### Back-end
* **Django** :FrameWork python pour Pour le developpement Web
## Front-end
* **Tailwind CSS** : FrameWork CSS pour le Front-End
* **Chart JS** : FrameWork JavaScript pour affichage des Graphes Dynamique 
## 4. **Installation**
### Prerequis
* Python 3.12
* Node.js(pour la gestion des dépendances front-end)
### Les etapes de l'installation
1. Clonez le depot :
2. Installez les dependances Python:
> pip install -r requirements.txt   
3. Appliquer les migrations du base de donnees:
> python manage.py migrate
4. Lancez `django_browser_reload`:
> python manage.py tailwind start
5. Lancez le serveur de developpement 
> python manage.py runserver
Acceder a l'applicaton via `http://127.0.0.1:8000`. 
## 5. **Utilisation**
Une fois l'application installée et le serveur en cours d'exécution, vous pouvez accéder à l'interface utilisateur pour commencer à gérer les patients et les rendez-vous. Utilisez les fonctionnalités de l'application pour ajouter des patients, planifier des rendez-vous, et consulter les statistiques.



