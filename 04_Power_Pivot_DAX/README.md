04 — Power Pivot & DAX

Cette section présente mon apprentissage de Power Pivot et du langage DAX pour construire un modèle de données et réaliser des analyses plus avancées avec Excel.

🎯 Objectif

Apprendre à modéliser plusieurs tables de données, créer des relations entre elles et construire des indicateurs dynamiques à l'aide de DAX.

📚 Contenu
Jour	Thème
J23	Modèle de données avec Power Pivot
J24	Introduction à DAX et création de mesures
🧩 Power Pivot

Les exercices portent notamment sur :

Importation des données dans le modèle de données
Création de relations entre les tables
Organisation des tables dans un modèle analytique
Création de tableaux croisés dynamiques à partir du modèle
Construction d'un modèle de type étoile
Analyse des ventes par produit, vendeur et autres dimensions
Modèle utilisé
             Produits
                │
                │
Vendeurs ──── Ventes

La table Ventes constitue la table de faits, tandis que Produits et Vendeurs jouent le rôle de tables de dimensions.

📐 DAX

Les exercices permettent de travailler notamment :

SUM
SUMX
CALCULATE
FILTER
RELATED
Les mesures
Le contexte de filtre
Les calculs dynamiques
Exemple de mesure
CA_Total := SUM(Ventes[CA])

Les mesures sont ensuite utilisées dans les tableaux croisés dynamiques pour analyser les indicateurs selon différents contextes de filtre.

🛠️ Compétences travaillées
Modélisation des données
Relations entre tables
Modèle en étoile
Tableaux croisés dynamiques basés sur un modèle de données
Création de mesures DAX
Analyse selon le contexte de filtre
Calcul d'indicateurs de performance (KPI)
📁 Organisation
04_Power_Pivot_DAX/
├── day_23/
└── day_24/

