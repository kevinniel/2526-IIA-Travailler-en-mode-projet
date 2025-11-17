# TP

## Énoncé de départ

Une PME souhaite moderniser son infrastructure informatique. Elle dispose aujourd’hui d’un simple routeur internet et de 5 postes reliés en Wi-Fi.

Elle souhaite désormais :

- Mettre en place un réseau local structuré (avec VLAN, adressage, switch manageable)
- Héberger un serveur interne (Windows Server ou Debian) pour la gestion des fichiers et utilisateurs
- Sécuriser les accès (pare-feu, segmentation, sauvegarde)
- Avoir une solution de supervision simple (type Zabbix, GLPI, Centreon, etc.)

Les informations supplémentaires : 
- Le client est chez Orange Pro pour internet
- On ne forme personne en interne
- Pas d'info sur le budget, je laisse ouvert aux propositions

## 1 — Analyse du besoin

### Consignes

Rédige un compte rendu d’entretien client (réel ou simulé).

Rédige une analyse de l’existant :

- schéma réseau actuel
- inventaire matériel / logiciel
- identification des contraintes (budget, compétences, délais)
- Fais une analyse des risques : panne, sécurité, erreurs humaines, etc.

### Livrables

- Compte rendu client
- Analyse de l’existant
- **Tableau des risques**

## 2 — Cahier des charges fonctionnel

### Consignes

Liste les besoins exprimés et implicites du client.

Définis les objectifs fonctionnels :

- disponibilité
- sécurité
- facilité d’administration

Rédige un cahier des charges fonctionnel avec :

- Objectifs généraux
- Fonctionnalités attendues
- Contraintes

### Livrables

- Cahier des charges fonctionnel (1 à 2 pages)
- **Cas d'utilisation** 

## 3 — Cahier des charges technique

### Consignes

Propose une architecture réseau cible :

- schéma logique et physique
- VLAN, IP, adressage, routage
- Indique les équipements choisis (modèle, OS, rôle).
- Justifie les choix techniques (sécurité, performance, coût).
- Élabore un plan d’adressage IP détaillé.
- Rédige une fiche technique par équipement.

### Livrables

- Cahier des charges technique
- Schéma réseau
- Plan d’adressage IP
- Tableau matériel / logiciels

## 4 — Conception détaillée

### Consignes

Rédige un dossier de conception détaillée contenant :

- les paramètres de configuration (IP, VLAN, routes, etc.)
- les scripts à prévoir (bash, powershell, batch)
- les étapes d’installation et de configuration
- Rédige un plan d’installation et de mise en service (ordre des tâches).

### Livrables

- Dossier de conception détaillée
- **Plan d’installation**

## 5 — Réalisation

### Consignes

Réalise l’installation et la configuration selon ton plan.

Note dans un journal d’intervention :

- la date / heure
- la tâche réalisée
- le temps passé
- les incidents éventuels

Crée un dossier de configuration complet :

- captures d’écran
- fichiers de conf
- scripts utilisés

### Livrables

- Journal d’intervention
- Dossier de configuration (documentation technique)

## 6 — Tests unitaires

### Consignes

Crée un plan de test unitaire (une ligne par fonctionnalité testée).

Teste individuellement :

- Ping inter-VLAN
- Connexion au serveur
- Authentification utilisateur
- Sauvegarde automatique
- Documente les résultats (OK / KO / observations).

📄 Livrables :

- **Plan de test** unitaire
- **Rapport d’anomalies**

## 7 — Tests d’intégration

Consignes :

Rédige un plan de test d’intégration (enchaînement complet d’un scénario).

Exemple :
- Un utilisateur se connecte, accède à un dossier partagé, lance une sauvegarde, et reçoit une alerte supervision.
- Documente les résultats et captures de test.
- Rédige un rapport de test d’intégration.

### Livrables

- Plan de test d’intégration
- **Rapport d’intégration**

## 8 — Validation / Recette

Consignes :

- Rédige un cahier de validation fonctionnel (reprend les exigences du cahier des charges).
- Le client (joué par le prof ou un autre groupe) valide chaque point (OK / KO).
- Rédige un PV de recette et un guide d’exploitation :
- procédures de sauvegarde
- supervision
- mises à jour

### Livrables

- Cahier de validation fonctionnel
- **PV de recette**
- Guide d’exploitation / maintenance

## 9 — Bilan de projet

Consignes :

Réalise une fiche de synthèse :
- ce qui a bien fonctionné
- les difficultés rencontrées
- les pistes d’amélioration

Évalue la gestion de projet :
- planification
- communication
- respect du temps / qualité

### Livrables

- Fiche bilan de projet
- Autoévaluation du groupe - à imaginer



A finaliser pour le 18 Novembre (17h).
A envoyer par mail à k.niel.pro@gmail.com 
1h de retard = 5 points en moins par heure.
Toute heure engagée est dûe.