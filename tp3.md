# TP3 

Gérer les projets suivant dans GanttProject.

## LVMH

LVMH vous demande de refaire son site marchand, en vous laissant 1 an pour tout réaliser.
Vous disposez des ressources suivantes : 

- Virgile (100€ TJM)
- Rémi (80€ TJM)
- Ylan (90€ TJM)
- Mahmoud (120€ TJM)
- Clément (40€ TJM)

Optimisez le projet pour qu'il coûte le moins cher possible, et déterminez le coûts total du projet.

| Tâche | Intitulé                                             | Durée | Prédécesseurs                   |
| ----- | ---------------------------------------------------- | ----- | ------------------------------- |
| A     | Cadrage & lancement (kick-off)                       | 5     | -                               |
| B     | Ateliers métier & vision produit                     | 10    | A                               |
| C     | Audit technique de l’existant                        | 7     | A                               |
| D     | Audit UX + analytics actuels                         | 6     | A                               |
| E     | Architecture cible (app, données, infra)             | 8     | B, C                            |
| F     | Guidelines de marque & design digital                | 7     | B                               |
| G     | Arborescence & parcours clés                         | 6     | B, D                            |
| H     | Exigences sécurité & conformité (GDPR, PCI)          | 4     | B, C                            |
| I     | Choix techno & outillage (CMS/headless, PIM, search) | 5     | E                               |
| J     | UX wireframes pages & funnels                        | 12    | G, F                            |
| K     | UI design system + maquettes haute fidélité          | 15    | J, F                            |
| L     | Intégration statique des maquettes (HTML/CSS)        | 12    | K                               |
| M     | Dév Frontend (framework, routing, state)             | 20    | L, I                            |
| N     | Dév Backend (APIs, CMS, PIM, auth)                   | 25    | E, I                            |
| O     | Intégration paiement (PSP, 3DS2, anti-fraude)        | 8     | N, H                            |
| P     | Intégration OMS/ERP (stocks, commandes, prix)        | 12    | N                               |
| Q     | Intégration CRM & marketing automation               | 8     | N                               |
| R     | Moteur de recherche & merchandising                  | 7     | N, I                            |
| S     | Internationalisation (i18n, multi-boutiques)         | 10    | N, G                            |
| T     | Import & nettoyage catalogue (PIM)                   | 12    | N                               |
| U     | SEO technique & contenu (spécifs + implémentation)   | 9     | L, G, H                         |
| V     | Optimisation performance (CWV)                       | 7     | M                               |
| W     | Accessibilité (WCAG 2.2 AA)                          | 6     | L                               |
| X     | Tests unitaires & d’intégration CI                   | 10    | M, N                            |
| Y     | Tests sécurité (pentest + remédiations)              | 7     | H, M, N                         |
| Z     | Recette fonctionnelle / UAT transverse               | 12    | X, O, P, Q, R, S, T, U, V, W, Y |
| AA    | Préparation infra & déploiement (CI/CD, cloud)       | 8     | E, C                            |
| AB    | Analytics & consent (GA4, TMS, CMP, events)          | 5     | U, Q                            |
| AC    | Formation équipes e-commerce & support               | 4     | Z                               |
| AD    | Go-Live                                              | 1     | AA, AB, AC                   |
| AE    | Hypercare & stabilisation post-lancement             | 10    | AD                              |


## HERMES

Hermès souhaite mettre en place un tunnel de vente simple et rapide pour tester un nouveau produit en ligne.
L’objectif est de créer un parcours client fluide (landing → produit → paiement), sans complexité technique, en un minimum de temps.
Le client veut le travail réalisé le plus rapidement possible.

| Tâche | Durée                                     | Prédécesseurs |         |
| ----- | ----------------------------------------- | ------------- | ------- |
| A     | Définir le parcours client                | 1             | -       |
| B     | Créer la landing page                     | 2             | A       |
| C     | Créer la page produit                     | 2             | A       |
| D     | Créer la page panier & checkout           | 2             | B, C    |
| E     | Configurer le paiement                    | 1             | D       |
| F     | Ajouter le tracking (GA4, Pixel)          | 1             | B, C, D |
| G     | Tests rapides (commande test, responsive) | 2             | E, F    |
| H     | Mise en ligne                             | 1             | G       |

## CARTIER

Cartier souhaite mettre en ligne un mini-catalogue vitrine (quelques produits, sans tunnel de paiement complet) avec un formulaire de prise de contact. Objectif : publier rapidement une sélection produit soignée, traçable et SEO-ready. Ca doit être mis en place avant Noël.

| Tâche | Intitulé                                                   | Durée | Prédécesseurs |
| ----- | ---------------------------------------------------------- | ----: | ------------- |
| A     | Définir la structure (catégories, fiches, champs)          |     2 | -             |
| B     | Préparer contenus textes (titres, descriptions, métas)     |     3 | A             |
| C     | Shooting/retouche photos produits (sélection courte)       |     4 | A             |
| D     | Maquette rapide (listing + fiche produit + contact)        |     2 | A             |
| E     | Mise en place CMS léger / collection (ex : Shopify simple) |     2 | A             |
| F     | Intégration listing (grille, tri, filtres simples)         |     3 | D, E          |
| G     | Intégration fiche produit (galerie, détails, variantes)    |     3 | D, E          |
| H     | Import des contenus & médias (textes B + photos C)         |     2 | B, C, G       |
| I     | Formulaire contact/devis (envoi mail + stockage)           |     2 | D, E          |
| J     | Tracking & consent (GA4, TMS/CMP basique)                  |     1 | F, G, I       |
| K     | SEO basique (métas, balises, sitemap, schema.org)          |     2 | B, F, G       |
| L     | Tests & corrections (mobile, perfs légères, formulaires)   |     3 | H, I, J, K    |
| M     | Mise en ligne mini-catalogue                               |     1 | L             |

## NOUVELLE CONTRAINTE

Les employés se rebellent parce que vous n'avez pas gérer les jours fériés Français !
Gérez la situation !

## GUCCI

GUCCI confie une refonte e-commerce premium. On vise un planning à gros blocs (tâches longues) pour limiter la micro-gestion.
Durée du projet maximale : 14 mois à partir de ce jour.

| Tâche | Intitulé                                                     | Durée | Prédécesseurs       |
| ----- | ------------------------------------------------------------ | ----: | ------------------- |
| A     | Cadrage stratégique & objectifs (scope, KPIs, priorités)     |    15 | -                   |
| B     | Discovery unifiée Tech + UX (audits, data, risques)          |    20 | A                   |
| C     | Architecture cible (app, données, infra)                     |    20 | B                   |
| D     | Parcours & wireframes des écrans clés                        |    25 | B                   |
| E     | UI design system & maquettes haute fidélité                  |    30 | D                   |
| F     | Intégration statique globale (HTML/CSS, composants)          |    20 | E                   |
| G     | Développement Frontend (PWA, routing, état, i18n)            |    35 | F, C                |
| H     | Développement Backend (APIs, auth, catalogue, panier)        |    40 | C                   |
| I     | Checkout & conformité paiement (PSP, 3DS2, PCI light)        |    20 | H                   |
| J     | Recherche & merchandising (moteur, règles, navigation)       |    15 | H                   |
| K     | Migration données & catalogue (qualité, mapping, imports)    |    20 | H                   |
| L     | Performance & accessibilité (CWV, WCAG 2.2 AA priorités)     |    15 | G                   |
| M     | Sécurité & remédiations (scan, pentest, durcissement)        |    15 | G, H, I             |
| N     | QA / automatisation & UAT métier                             |    20 | G, H, I, J, K, L, M |
| O     | CI/CD & préparation déploiement (environnements, monitoring) |    15 | C                   |
| P     | Go-Live                                                      |     2 | N, O                |
| Q     | Hypercare & stabilisation                                    |    15 | P                   |

## Des maladies chroniques en perspective

Plusieurs maladies ont eu lieues durant l'année, voici les dates concernées pour chaque personnes : 

Mahmoud
- 02/03/2026 → 01/08/2026

Ylan
- 12/01/2026 → 16/01/2026
- 08/07/2026 → 26/07/2026

Virgile
- 22/12/2025 → 02/01/2026
- 16/05/2026 → 20/05/2026
- 05/09/2026 → 09/09/2026

Rémi
- 02/01/2026 → 05/01/2026
- 10/04/2026 → 30/04/2026
- 01/08/2026 → 19/08/2026

Clément
- 24/12/2025 → 31/12/2025
- 08/03/2026 → 12/03/2026
- 27/06/2026 → 01/07/2026
- 22/08/2026 → 02/09/2026

## L'arrivée des vacances !

Mahmoud
- 06/10/2025 → 10/10/2025
- 27/10/2025 → 31/10/2025
- 01/12/2025 → 05/12/2025
- 23/02/2026 → 27/02/2026
- 17/08/2026 → 21/08/2026

Ylan
- 17/11/2025 → 21/11/2025
- 01/12/2025 → 05/12/2025
- 19/01/2026 → 23/01/2026
- 26/01/2026 → 30/01/2026
- 31/08/2026 → 04/09/2026

Virgile
- 20/10/2025 → 24/10/2025
- 10/11/2025 → 14/11/2025
- 27/04/2026 → 01/05/2026
- 22/06/2026 → 26/06/2026
- 13/07/2026 → 17/07/2026

Rémi
- 13/10/2025 → 17/10/2025
- 10/11/2025 → 14/11/2025
- 19/01/2026 → 23/01/2026
- 26/01/2026 → 30/01/2026
- 29/06/2026 → 03/07/2026

Clément
- 13/10/2025 → 17/10/2025
- 12/01/2026 → 16/01/2026
- 06/07/2026 → 10/07/2026
- 27/07/2026 → 31/07/2026
- 17/08/2026 → 21/08/2026

## Tuto de fin ! 

Au format PDF, réalisez une présentation "tuto" pour expliquer comment se servir de GanttProject.
Il est possible de faire un site internet pour cette présentation. Par contre, vous le mettez en ligne avec github pages !

Envoyer moi ça par mail à k.niel.pro@gmail.com