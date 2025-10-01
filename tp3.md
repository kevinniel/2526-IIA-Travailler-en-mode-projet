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
