# Travailler en mode projet

## Cours

1. <a href="cours/definitions.md" title="Définitions">Définitions</a>
2. <a href="cours/wbs.md" title="Work Breakdown Structure (WBS)">Work Breakdown Structure (WBS)</a>

## TP

1. <a href="tp1.md" title="Conception de site vitrine">Conception de site vitrine</a>
















------------------------------------
# NOTES
------------------------------------



- Cycle en V
- Méthodes agiles
- GANTT & PERT


Pour chacune des tâches, nous allons devoir : 
- Description de la tâche
- Délai
- Responsable de la tâche
- Prix
- Statut
- Quels autres tâches sont necessaires pour démarrer ma tâche, dans quel ordre je dois faire cette tâche ?



12€ / heure = 420€
- Projet de site vitrine (35h)
    - (A) Choisir les technologies (1h)
        - Choisir un hébergeur
        - Le Front
        - Le Back
        - Analytics
    - (B) Maquettage (14h)
        - Zonning => c'est le positionnement des éléments sur une page
        - Wireframe => c'est un zonning cliquable (qui permet de naviguer d'une page à une autre)
        - Maquette => la version graphique du zonning
        - Prototype => c'est l'équivalent du wireframe, mais avec des maquettes graphiques finalisées.
    - (C) Arborescence (2h)
        - Définition des pages
        - Définition du contenu de chaque page
    - (D) Développer le site (14h)
        - Front
        - Back
    - (E) Recettage (4h)
        - Mettre en production
        - Tester
        - Valider


1. fixer une "plage horaire" plutôt que des heures fixes
2. Qu'est-ce qu'on met dans quel sens ?

Antécédant = quelle tâche doit-on faire avant les autres ?


| Tâche | Durée | Antécédants | 
| --- | --- | --- | 
| A | 1-1 |  | 
| B | 14-18 | A,C | 
| C | 2-4 |  | 
| D | 14-21 | B | 
| E | 4-7 | D | 

------------------------

J'ai besoin de visualiser les choses

Faire un schéma, avec des ronds qui représentent l'enchainement des tâches

(A, C) => B => D => E

------------------------

Il y a 2 marges différentes : 

- **marge "totale"** : elle représente le retard que peut prendre la réalisation d'une tâche sans
impacter la date de fin du projet (à condition qu'elle ait commencé à sa date le plus tôt)
- **marge "libre"** : elle correspond au retard que peut prendre la réalisation d'une tâche sans
impact sur la date au plus tôt des tâches suivantes (à condition qu'elle ait débuté à sa date le plus
tôt).

Formule de la marge totale : 
```
Date au plus tard de l'étape suivante - Durée de la tâche - Date au plus tôt de l'étape précédente
```

Formule de la marge libre : 
```
Date au plus tôt de l'étape suivante - Durée de la tâche -  Date au plus tôt de l'étape précédente
```










------------------------

## Exemple 1 : Faire un nouveau site internet vitrine, pour présenter mon activité

### Demande client : Expression des besoins

Faire un nouveau site internet vitrine, pour présenter mon activité
Je veux pouvoir modifier les contenus
Je veux que le site soit responsive
Je veux quele site soit bien référencé
Je veux qu'il soit accessible

### Plannifier

1. Préciser la demande client et analyser l'ensemble du projet, identifier les besoins.
2. Devis
    - Précision des Délais
    - Prix
3. Cahier des charges
    - Fonctionnels
    - Techniques
    - Plannification
4. Contrat de prestation


- le but ? => OK
- quel type de société ? => SAS
- ce qui doit être mis en avant => OK
- charte graphique ? => je n'en ai pas
- voir des exemples 
- identifier les éléments d'une charte graphique
- Hébergement