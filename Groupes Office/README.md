# 2. Gouvernance des Groupes Office
- Quel modèle de mise en service répond aux besoins de votre organisation ?
- Votre organisation a-t-elle besoin de limiter la création de groupes aux administrateurs ?
- Votre organisation a-t-elle besoin de limiter la création de groupe aux membres du groupe de sécurité ?
- Votre organisation a-t-elle besoin de créer des groupes de manière dynamique en fonction des attributs des utilisateurs, tels que service ?
= Votre annuaire AD est-il utilisé conformément aux recommandations? Utilisez-vous des attributs personnalisés?
- Votre annuaire fait-il apparaitre l’information Manager?
- Votre annuaire fait-il apparaitre l’information Depatment?
- Souhaitez-vous faire apparaitre tous les groupes dans votre Liste d’Adresse Globale (GAL)? Ou seulement une sorte de groupes? Comment les identifier?

## 1.	Rôles et responsabilités
- Qui prend ou valide les décisions?
## 2.	Règles d’archivage et de retention
- Avez-vous besoin que certains biens soient archivés pour le stockage à long terme ?
- Existe-t-il des exigences en matière de rétention pour votre organisation ?
## 3.	Convention de nommage
- Votre organisation a-t-elle besoin d’une convention d’affectation de noms spécifique pour les groupes ?
- Votre organisation a-t-elle besoin de la Convention d’affectation de noms pour toutes les charges de travail ?
- Votre organisation a-t-elle des mots spécifiques que vous souhaitez empêcher les utilisateurs d’utiliser ?
## 4.	Expiration des groupes
- Votre organisation a-t-elle besoin de spécifier une date d’expiration pour teams ?
- Déterminer la stratégie de traitement des groupes orphelins ?
## 5.	Utilisateurs Externes (invités)
- Avez-vous besoin de limiter la possibilité d’ajouter des invités à teams par groupe ?
- Votre organisation a-t-elle besoin de présenter des clauses d’exclusion de responsabilité pertinentes pour les besoins légaux ou de conformité ?
- Votre organisation a-t-elle besoin de réduire la charge administrative de l’ajout et de la suppression d’utilisateurs ?
- Votre organisation prévoit-elle des contrôles d’audit pour l’accès invité/externe ?
## 6.	Sécurité et conformité
- Votre organisation a-t-elle des exigences d’utilisation spécifiques qui doivent être communiquées à tous les utilisateurs ?
- Votre organisation a-t-elle besoin des classifications de tout le contenu ?
- Votre organisation nécessite-t-elle la conservation du contenu pendant une période de temps spécifique ?
- Votre organisation nécessite-t-elle des stratégies de rétention de données spécifiques ? plied à des groupes ?
- Votre organisation a-t-elle besoin d’avoir la possibilité d’archiver des groupes inactifs pour conserver le contenu ?
- Les créateurs de groupe doivent-ils pouvoir attribuer des classifications spécifiques de l’organisation à teams ?
## 7.	Listes de distributions actuelles
- Votre organisation a-t-elle des listes de distribution qui ne sont pas éligibles pour la mise à niveau ?
- Déterminez le type de groupe sur lequel la liste de distribution est la mieux migrée.
## 8.	Analyse et reporting
- Votre organisation a-t-elle besoin de rapports réguliers pour comprendre l’utilisation des groupes Office 365 ?
- Votre organisation a-t-elle besoin de rapports sur tous les groupes qui ont des membres externes ?

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
