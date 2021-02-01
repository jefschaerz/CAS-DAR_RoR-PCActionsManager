# CAS-DAR_RoR-PCActionsManager
Application écrite en Ruby on Rails pour gérer les interventions réalisés sur des équipement informatique.

<a name="top"></a>
Ce repository contient les sources du projet "PCActionManager" réalisé dans le cadre du CAS-DAR RoR / 2021.

- [Description de l'application](#description-application)
- [Utilisation de l'application](#utilisation-application)
- [Choix lors du développpement](#choix-developpement)
- [Ressources externes](#ressources-externes)
- [Améliorations possibles](#ameliorations)
- [Remarques sur le projet](#remarques-projet)
- [Info pour lancement de l'application](#lancement-application)

<a name="description-application"></a>
# Description de l'application
L'application "PCActionManager" permet à des utilisateurs de type "Admin" ou "User" de saisir des informations sur les actions réalisés 
sur des équipements informatiques plusieurs type (PC, serveurs ou imprimantes).

L'utilisateur doit d'abord se connecter dans l'application avec son nom d'utilisateur et mot de passe.
Deux type d'utilisateur sont possibles :
* L'utilisateur "Admin" a le droit de créer/modifier ou effacer des équipements. 
	Il peut également effectuer les opérations du "User".
* L'utilisateur "User" ne peut que créer ou modifier des interventions sur des équipements.

Les équipements possède le informations suivantes :
* No d'équipement (unique)
* Description (ex PC001)
* Type (PC ou Serveur ou Imprimante)

Les interventions sont créées en fournissant les informations :
* No intervention (unique)
* Date d'intervention
* Choix de l'équipement (ci-dessus)
* Description de l'intervention
* Détails de l'intervention
* Eventuellement : Etat de l'intervention (Ouvert, Clos)

<a name="choix-developpementn"></a>
# Choix du développpement
A décrire..


<a name="ressources-externes"></a>
# Ressources externes
A décrire..


<a name="remarques-projet"></a>
# Remarque sur le projet
A décrire..

