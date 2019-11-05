# Plan-de-gouvernance-M365
Un plan de gouvernance libre et Open-Source pour faciliter sa mise en place dans vos projets

## Sommaire




# 0. Qu’est-ce que la gouvernance?

# 1. Gouvernance générale Microsoft 365
## 1. Rôles et responsabilités

Rôle | Responsabilités | Nom
--------------------------------------------------------------------------------------------
Administrateur global |
Administrateur Réseaux |

## 2. Révision du plan de gouvernance
## 3. Mesure du plan de gouvernance
## 4. Plan de remédiation
## 5. Plan pédagogique
## 6. Support

#2. Gouvernance Groupes Office 365
•	Quel modèle de mise en service répond aux besoins de votre organisation ?
•	Votre organisation a-t-elle besoin de limiter la création de groupes aux administrateurs ?
•	Votre organisation a-t-elle besoin de limiter la création de groupe aux membres du groupe de sécurité ?
•	Votre organisation a-t-elle besoin de créer des groupes de manière dynamique en fonction des attributs des utilisateurs, tels que service ?
•	Votre annuaire AD est-il utilisé conformément aux recommandations? Utilisez-vous des attributs personnalisés?
•	Votre annuaire fait-il apparaitre l’information Manager?
•	Votre annuaire fait-il apparaitre l’information Depatment?
•	Souhaitez-vous faire apparaitre tous les groupes dans votre Liste d’Adresse Globale (GAL)? Ou seulement une sorte de groupes? Comment les identifier?
## 1.	Rôles et responsabilités
•	Qui prend ou valide les décisions?
## 2.	Règles d’archivage et de retention
•	Avez-vous besoin que certains biens soient archivés pour le stockage à long terme ?
•	Existe-t-il des exigences en matière de rétention pour votre organisation ?
## 3.	Convention de nommage
•	Votre organisation a-t-elle besoin d’une convention d’affectation de noms spécifique pour les groupes ?
•	Votre organisation a-t-elle besoin de la Convention d’affectation de noms pour toutes les charges de travail ?
•	Votre organisation a-t-elle des mots spécifiques que vous souhaitez empêcher les utilisateurs d’utiliser ?
## 4.	Expiration des groupes
•	Votre organisation a-t-elle besoin de spécifier une date d’expiration pour teams ?
•	Déterminer la stratégie de traitement des groupes orphelins ?
## 5.	Utilisateurs Externes (invités)
•	Avez-vous besoin de limiter la possibilité d’ajouter des invités à teams par groupe ?
•	Votre organisation a-t-elle besoin de présenter des clauses d’exclusion de responsabilité pertinentes pour les besoins légaux ou de conformité ?
•	Votre organisation a-t-elle besoin de réduire la charge administrative de l’ajout et de la suppression d’utilisateurs ?
•	Votre organisation prévoit-elle des contrôles d’audit pour l’accès invité/externe ?
## 6.	Sécurité et conformité
•	Votre organisation a-t-elle des exigences d’utilisation spécifiques qui doivent être communiquées à tous les utilisateurs ?
•	Votre organisation a-t-elle besoin des classifications de tout le contenu ?
•	Votre organisation nécessite-t-elle la conservation du contenu pendant une période de temps spécifique ?
•	Votre organisation nécessite-t-elle des stratégies de rétention de données spécifiques ? plied à des groupes ?
•	Votre organisation a-t-elle besoin d’avoir la possibilité d’archiver des groupes inactifs pour conserver le contenu ?
•	Les créateurs de groupe doivent-ils pouvoir attribuer des classifications spécifiques de l’organisation à teams ?
## 7.	Listes de distributions actuelles
•	Votre organisation a-t-elle des listes de distribution qui ne sont pas éligibles pour la mise à niveau ?
•	Déterminez le type de groupe sur lequel la liste de distribution est la mieux migrée.
## 8.	Analyse et reporting
•	Votre organisation a-t-elle besoin de rapports réguliers pour comprendre l’utilisation des groupes Office 365 ?
•	Votre organisation a-t-elle besoin de rapports sur tous les groupes qui ont des membres externes ?

Fonctionnalité	Détails	Licence Azure AD Premium requise	Décision
Stratégie de noms de groupes	Utiliser des mots bloqués personnalisés à l’aide de suffixe-suffixe.	P1	À déterminer
Classification de groupe	Affecter des classifications à Teams.	P1	À déterminer
Accès invité de groupe	Autoriser ou empêcher l’ajout d’invités à des groupes.	Non	À déterminer
Création de groupe	Limitez la création d’équipe aux administrateurs.	Non	À déterminer
Création de groupe	Limitez la création d’équipe aux membres du groupe de sécurité.	P1	À déterminer
Instructions relatives à l’utilisation des groupes	Définir un lien les instructions d’utilisation de groupe qui seront visibles sur tous les points de terminaison de création de groupe.	P1	À déterminer
Appartenance masquée	Masquer les membres du groupe Office 365 des utilisateurs qui ne sont pas membres du groupe	Non	À déterminer
Stratégie d’expiration	Gérer le cycle de vie des groupes Office 365 en définissant une stratégie d’expiration.	P1	À déterminer
Rapports d’activité de groupe	Accédez à l’activité des groupes Office 365 au sein de votre organisation et découvrez le nombre de groupes Office 365 créés et utilisés.	Non	À déterminer
Stratégie de rétention	Conserver ou supprimer des données pour une période spécifique en définissant des stratégies de rétention pour les groupes Office 365 dans le centre de sécurité & conformité. Remarque : Pour utiliser cette fonctionnalité, vous devez disposer des licences d’Office 365 entreprise E3 ou version ultérieure.	Non	À déterminer
Stratégie de protection contre la perte de données	Identifier les informations sensibles sur les sites connectés à un groupe Office 365 et empêcher le partage accidentel. Remarque : Pour utiliser cette fonctionnalité, vous devez disposer des licences d’Office 365 entreprise E3 ou version ultérieure.	Non	À déterminer
Archivage et restauration	Archivez une équipe lorsqu’elle n’est plus active, mais que vous souhaitez la conserver pour référence ou la réactiver ultérieurement.	Non	À déterminer
Révisions d’accès	Effectuer des révisions pour gérer efficacement les appartenances aux groupes pour les utilisateurs internes et invités	P2	À déterminer
Conditions d’utilisation	Méthode simple que les organisations peuvent utiliser pour présenter des informations aux utilisateurs finaux. Cette présentation permet aux utilisateurs de voir les clauses d’exclusion de responsabilité correspondant aux exigences légales ou de conformité.	P1	À déterminer

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

# 4. Gouvernance Microsoft Power Platform
## 1. Rôles et responsabilités
# 5. Gouvernance Microsoft Power Apps
## 1. Rôles et responsabilités
# 6. Gouvernance Microsoft Power Automate
## 1. Rôles et responsabilités
# 7. Gouvernance Microsoft Power BI
## 1. Rôles et responsabilités
# 8. Gouvernance SharePoint
## 1. Rôles et responsabilités
# 9. Gouvernance OneDrive for Business
## 1. Rôles et responsabilités
# 10. Gouvernance Hybride
## 1. Rôles et responsabilités
