# 3. Gouvernance Microsoft Teams
## 1.	Rôles et responsabilités
Rôle	Responsabilités	Nom
Administrateur Teams	Accès total aux équipes & Centre d’administration Skype, gère les groupes et les demandes de service Office 365, et surveille l’état du service.	
Gestionnaire de communication teams	Affecte des numéros de téléphone, crée et gère des stratégies de voix et de réunion, et lit l’analyse des appels.	
Ingénieur de support de communication teams	Lit les détails des enregistrements d’appel pour tous les participants aux appels afin de résoudre les problèmes de communication.	
Spécialiste de la prise en charge de la communication teams	Lit les détails de l’appel utilisateur uniquement pour un utilisateur spécifique afin de résoudre les problèmes de communication.	
	Définit les conventions de nommage des Équipes Microsoft Teams	
	Définit les classifications à mettre en place pour identifier les équipes Microsoft Teams	
	Créé les Équipes Microsoft Teams conformément aux conventions de nommage et de classification	
Propriétaires de l’équipe	Les propriétaires sont en charge de la gestion des contenus et de l’animation des interactions. Ils peuvent ajouter des canaux et ajouter des onglets aux canaux. Ils doivent modérer les conversations du canal principal.	
Membres de l’équipe	Les membres sont amenés à collaborer au contenu en réagissant dans les discussions et en partageant des documents 	
 
## 2.	Conventions de nommage des équipes Microsoft Teams
Définir ici les noms qui doivent être bloqués lors de la création de nouvelles équipes.
Définir le préfixe qui doit être utilisé dans la convention de nommage pour identifier plus facilement les groupes dans votre annuaire.
Les noms ne doivent pas utiliser des caractères accentués ou des caractères spéciaux.
## 3.	Classification des équipes Microsoft Teams
Il est essentiel de mettre en place une classification des équipes pour en faciliter l’identification et surtout éduquer les utilisateurs rapidement comprendre la gouvernance de chacun des types d’équipe.
Définir ici quelle sera la classification utilisée. Par exemple :
Nom	Description
Service	Les membres du service sont automatiquement ajoutés. Uniquement pour du contenu interne et limité aux membres du service. Ces services ne sont pas limités dans le temps.
Communaute	Les membres peuvent demander à rejoindre. Uniquement pour du contenu interne mais disponible à tous. Ces communautés ne sont pas limitées dans le temps.
Projet	Les membres du projet sont ajoutés par le chef du projet. Uniquement pour du contenu interne et limité aux membres du projet. Ces projets sont limités dans le temps.
Extrerne	Les membres du projet sont ajoutés par le propriétaire et peuvent être des utilisateurs Externes. Aucun contenu sensible ne doit être conservé dans cet espace dont la vie est limitée dans le temps.

## 4.	Ouverture des équipes Microsoft Teams aux utilisateurs externes invités
Définir ici si il sera possible et qui sera en charge d’inviter des utilisateurs externes.
Ces utilisateurs apparaitront dans votre annuaire Azure Active Directory. Ils n’utiliseront pas les licences mais devront avoir la licence nécessaire pour accéder aux applications que vous souhaitez leur partager. Il est important de mettre en place un script PowerShell permettant de « nettoyer » cette liste d’utilisateurs après que l’équipe Externe ait été archivée.
## 5.	Création des équipes Microsoft Teams
Définir ici qui sera en charge de la création des équipes et quel sera le processus.
La demande doit être effectuée auprès du centre de service. Mais faut-il que la demande soit validée avant d’en lancer la création par le centre de service.
Le compte de service Teams@ccq.org doit être ajouté comme administrateur secondaire à chaque création d’équipe.
Nom	Procédure de création et mise à disposition
Service	
Communaute	
Projet	
Extrerne	

## 6.	Définition de la date d’expiration
Définir ici si une date d’expiration automatique doit être mise en place. Une fois la date arrivée, le propriétaire de l’équipe recevra une notification lui demandant de prolonger la date si nécessaire. 
Nom	Date d’expiration
Service	
Communaute	
Projet	
Extrerne	

## 7.	Définition des règles de rétention
Définir si les informations contenues dans l’espace Teams doit suivre des règles particulières de conservation.
Nom	Règles de rétention
Service	
Communaute	
Projet	
Extrerne	

## 8.	Définition des règles d’archivage
Définir ici si l’équipe Teams doit être placée en mode Archive et garder ainsi le contenu consultable en lecture seule par les membres.
Nom	Règles d’archivage
Service	
Communaute	
Projet	
Extrerne	
