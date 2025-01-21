# Onyx Data January Challenge - Merchandise Sales Dashboard

## 📄 Contexte du projet
Lee Chatmen est un influenceur populaire aux États-Unis avec plus de 7 millions d’abonnés sur TikTok. Il s’est fait connaître grâce à ses vidéos divertissantes où il joue des chansons célèbres sur des guitares miniatures. En 2023, Lee a lancé sa propre ligne de produits dérivés.

Cette analyse explore les performances des ventes de sa ligne de marchandises et cherche à répondre à des questions clés à partir des données.

---

## 🎯 Questions clés
1. Quelles sont les tendances générales des ventes ?
2. Quelles catégories de produits performent le mieux ?
3. Quels sont les produits les plus et les moins populaires ?
4. Quel est l’impact de la localisation sur les performances des ventes ?
5. Quel est le profil démographique des acheteurs ?
6. Comment les avis et les notes des produits sont-ils corrélés avec les ventes ?
7. Quelles sont les tendances concernant les frais d’expédition ?
8. Les remises ou promotions influencent-elles les comportements d’achat ?
9. Existe-t-il des modèles dans les achats répétés ?

---

## 🛠️ Création du tableau de bord
Le tableau de bord a été conçu directement avec **Power BI**, en utilisant un dataset propre, ce qui a permis de se concentrer sur l’analyse et la segmentation des données. Voici les étapes suivies :

### Étapes principales
1. **Inspection des données** :
   - Exploration rapide des colonnes disponibles, avec un focus sur leur pertinence pour l’analyse.
   - Les données étaient propres, ce qui a réduit les efforts nécessaires pour le nettoyage.

2. **Segmentation des données** :
   - Création de segments pertinents pour enrichir les analyses :
     - **Âge et sexe** : Pour comprendre les comportements démographiques.
     - **Pays** : Pour analyser les performances géographiques.
     - **Ratings (Notes)** : Catégorisation en **positive**, **neutre**, et **negative**.
     - **Reviews (Avis)** : Regroupement des commentaires en thèmes (**review category**).
     - **Tranches de prix** : Analyse des performances par niveaux de prix.
     - **Discount/No Discount** : Pour évaluer l’impact des promotions.

3. **Visualisations** :
   - Utilisation de graphiques interactifs avec un design axé sur le **cross-filtering** (aucun slicer utilisé).
   - Visualisations principales :
     - **Tendances des ventes mensuelles** avec cumul.
     - **Répartition des ventes par catégorie de produit**.
     - **Analyse géographique des ventes** par pays et région.
     - **Impact des frais de livraison sur les ventes et l’AOV**.
     - **Impact des remises et promotions**.

4. **Design et interactivité** :
   - Ajout de cartes KPI pour les indicateurs clés : ventes totales, nombre de commandes, valeur moyenne des commandes.
   - Utilisation de **ZoomCharts** pour maximiser l’interactivité et offrir une expérience utilisateur fluide.

---

## 📊 Insights clés

### Vue d’ensemble des ventes
- Les ventes totales atteignent **856 000 $**, générées par **7 394 commandes** et **12 334 produits vendus**.
- La **valeur moyenne des commandes (AOV)** est de **116 $**, avec une moyenne de **1,68 produit par commande**.
- Les ventes augmentent régulièrement au fil du temps, sans montrer de pics significatifs, indiquant une base de clients fidèle et un intérêt constant pour les produits.

### Vue d’ensemble
![Vue d’ensemble](images/Capture%20d’écran%202025-01-21%20-%20Overview.png)

---

### Performances des ventes
- Les **États-Unis** représentent **84 % des ventes totales**, soit **470 000 $**. Cela s’explique par :
  - **Les frais de livraison internationaux**, qui freinent les commandes depuis d’autres régions.
  - **La popularité de Lee Chatmen aux États-Unis**, où il est basé et bénéficie d’une forte notoriété.
- **Sydney est la ville avec le plus de ventes dans le monde**, représentant **6 % des ventes totales**, malgré des frais de livraison élevés.
- **Austin a enregistré la plus forte croissance des ventes sur la période**, avec une augmentation de **16 %**, indiquant une adoption croissante des produits dans cette région.
- En dehors des États-Unis, l’Europe (25 %) et l’Inde (6 %) montrent un intérêt notable pour les produits.

### Performances des ventes
![Performances des ventes](images/Capture%20d’écran%202025-01-21%20-%20Sales%20Performance.png)
### Détails des ventes
![Détails des ventes](images/Capture%20d’écran%202025-01-21%20-%20Sales%20Details.png)

---

### Performances des produits
- La catégorie **Clothing** domine les ventes, représentant **75 %** du total (637K$), suivie des **Ornaments** (156K$) et des produits divers (63K$).
- Le produit **BF1548** est le plus vendu, générant **190 640 $**, soit **30 % des ventes totales**.
- Les produits **BF1550** et **BF1551** enregistrent les **plus forts taux de croissance** sur la période, avec des augmentations de **12 % et 13 %** respectivement.
- Les produits dont le prix se situe entre **50 et 100 $** génèrent le **plus grand total de ventes**, soulignant une forte préférence des clients pour cette gamme de prix.

### Performances des produits
![Performance des produits](images/Capture%20d’écran%202025-01-21%20-%20Products%20Performance.png)
### Détails des produits
![Détails des produits](images/Capture%20d’écran%202025-01-21%20-%20Products%20Details.png)

---

### Satisfaction client et avis
- **60 % des avis sont positifs**, avec une note moyenne de **3,50 étoiles**.
- **Top 3 des critiques positives** :
  1. **Qualité et fabrication** : Les clients apprécient la qualité des matériaux et des produits.
  2. **Livraison et expédition** : Retours positifs sur les délais de livraison raisonnables.
  3. **Prix et valeur** : Les produits offrent un bon rapport qualité-prix.
- **Top 3 des critiques négatives** :
  1. **Qualité et fabrication** : Défauts ou attentes non respectées.
  2. **Livraison et expédition** : Retards ou coûts élevés.
  3. **Attentes vs réalité** : Produits ne correspondant pas toujours aux attentes des clients.

### Satisfaction client
![Satisfaction client](images/Capture%20d’écran%202025-01-21%20-%20Customer%20Satisfaction%20%26%20Shipping.png)

---

## 📈 Recommandations
1. **Exploiter les produits performants :**
   - Étendre la gamme **Clothing** avec de nouvelles collections.
   - Promouvoir les produits à forte croissance comme **BF1550** et **BF1551**.

2. **Réduire les barrières liées aux frais d’expédition :**
   - Proposer des **remises sur les frais de livraison internationaux**.
   - Mettre en place un **seuil de livraison gratuite**, par exemple pour les commandes supérieures à 100 $.

3. **Améliorer la satisfaction client :**
   - Renforcer le contrôle qualité.
   - Réaligner les descriptions et visuels des produits.

---

## 🛠️ Outils et technologies
- **Power BI** : Création du tableau de bord interactif.
- **ZoomCharts** : Interactivité avancée.

---

## 📥 Fichiers inclus
- **Merchandise_Sales_Dashboard.pbix**
- **README.md**
- **Images** (dossier `images/`)

---

### 🌟 Remerciements
Merci à **Onyx Data**, **ZoomCharts**, et **DataDNA** pour ce challenge et le dataset.
