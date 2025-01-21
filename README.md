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
5. Quel est l’impact des livraisons internationales sur les ventes ?
6. Quel est le profil démographique des acheteurs ?
7. Comment les avis et les notes des produits sont-ils corrélés avec les ventes ?
8. Quelles sont les tendances concernant les frais d’expédition ?
9. Comment les remises ou les prix promotionnels influencent-ils les achats ?
10. Existe-t-il des modèles dans les achats répétés ?

---

## 🛠️ Construction du tableau de bord
Le tableau de bord a été conçu en suivant une approche structurée et s’appuie sur les visualisations avancées de ZoomCharts pour améliorer l’interactivité. Voici les étapes principales :

- **Préparation des données** :
  - Nettoyage et profilage des données avec Excel et SQL.
  - Création de deux vues dans SQL : une vue détaillée pour les analyses produit et une vue agrégée pour les analyses globales.
  
- **Exploration des données (EDA)** :
  - Analyse des distributions et des relations entre les variables.
  - Création d’une colonne "Âge" pour catégoriser les clients par tranche d’âge (Jeunes, Adultes, Seniors).

- **Visualisations dans Power BI** :
  - Absence de slicers : Le tableau de bord mise sur le cross-filtering entre les graphiques pour filtrer dynamiquement les données.
  - Conception de graphiques clés :
    - Graphique des ventes mensuelles avec tendances cumulées.
    - Répartition des ventes par catégorie de produit.
    - Analyse géographique des performances des ventes.
    - Corrélation entre les avis/notes et les ventes.

- **Mise en page et interactivité** :
  - Utilisation d’icônes pour accéder facilement à des sections spécifiques (Ventes globales, Clients, Performance des produits).
  - Création d’une hiérarchie drill-down pour visualiser les tendances des ventes par mois, semaine et jour.

---

## 📊 Insights clés
### Ventes générales
- Les ventes atteignent un total de **856 000 $**, avec une moyenne de **116 $ par commande**.
- Les tendances montrent une forte augmentation des ventes en milieu d’année, suivie d’une légère baisse vers la fin.

### Performance des produits
- La catégorie **"Clothing"** domine les ventes, représentant **74 % du total**, suivie par **"Ornaments"**.
- Les produits les moins populaires incluent des accessoires moins coûteux (câbles, etc.).

### Analyse géographique
- Les États-Unis génèrent **84 % des ventes**, suivis par l’Europe (**25 %**) et l’Inde (**6 %**).
- Les frais de livraison internationaux affectent significativement les ventes dans certaines régions.

### Comportement des clients
- Les acheteurs appartiennent majoritairement à la catégorie d’âge **Adulte (25-44 ans)**.
- Les notes et avis influencent directement les ventes : les produits bien notés obtiennent des volumes de ventes plus élevés.

---

## 🖼️ Captures d’écran
*(Ajoute ici des captures d’écran du tableau de bord)*

---

## 🛠️ Outils et technologies
- **Power BI** : Pour la création du tableau de bord interactif.
- **ZoomCharts** : Pour une expérience utilisateur fluide avec des visualisations dynamiques.
- **SQL (Workbench)** : Pour les agrégations et le nettoyage des données.
- **Excel** : Pour l’exploration initiale des données.

---

## 📥 Fichiers inclus
- **Tableau de bord Power BI** : `Merchandise_Sales_Dashboard.pbix`
- **README.md** : Ce fichier.
- **Captures d’écran** : Disponibles dans le dossier `screenshots/`.

---

### 🌟 Remerciements
Merci à **Onyx Data**, **ZoomCharts**, et **DataDNA** pour l’organisation de ce challenge et la fourniture du dataset.

---
