# README - Génération de Données E-commerce

## 📌 Description

Les données des boutiques e-commerce sont difficilement accessibles, surtout au Sénégal. Pour pallier ce manque, ce script Python génère des **données synthétiques cohérentes** pour une boutique e-commerce, en vue d'une analyse ultérieure. Les données produites sont réalistes et prennent en compte les tendances saisonnières, les pics de vente par produit et les comportements des utilisateurs.

## 📂 Données Générées

Le script crée **quatre jeux de données** sous forme de fichiers CSV :

1. **Catalogue Produits (********`catalogue_produits.csv`********)**

   - Contient 5000 produits appartenant à 16 catégories (Smartphones, Jeux Vidéo, Électroménager, etc.).
   - Inclut le nom du produit, sa catégorie et son prix.

2. **Historique des Ventes (********`historique_ventes.csv`********)**

   - Enregistre 50 000 commandes passées sur le site.
   - Prend en compte des pics de ventes spécifiques à chaque produit (ex: iPhone en septembre et décembre, Crème solaire en juin et juillet).
   - Inclut la date de vente, l'identifiant du produit, la quantité achetée et le montant total.

3. **Clickstream (Interactions Utilisateurs) (********`clickstream.csv`********)**

   - Simule 100 000 interactions des utilisateurs avec les produits (ajout au panier, consultation, achat, etc.).
   - Pondération des actions selon les périodes de forte activité (décembre, janvier, juin, juillet, août).

4. **Tendances Externes (********`tendances_externes.csv`********)**

   - Indique la popularité des produits en fonction des événements clés (Soldes, Black Friday, Rentrée scolaire, etc.).
   - Permet de comparer la corrélation entre tendances et ventes.

## 🛠️ Prérequis

Avant d'exécuter le script, assurez-vous d'avoir **Python 3.x** installé, ainsi que les bibliothèques suivantes :

```sh
pip install pandas faker matplotlib
```

## 📊 Analyse Possible

- **Identification des pics de vente** et impact des tendances.
- **Analyse des comportements utilisateurs** (fréquence d'achat, panier moyen, produits populaires).
- **Prédiction des ventes et gestion du stock** en fonction des tendances historiques.

## 📝 Notes

- Les périodes de forte activité sont **configurables** via le dictionnaire `pics_de_ventes` dans le script.
- Ce jeu de données est fictif mais suit une **logique réaliste basée sur des tendances réelles**.

## 📧 Contact

Pour toute question ou amélioration, contactez github: lemar00.

---

🎯 **Objectif : Permettre une analyse avancée des tendances et comportements sur un site e-commerce !** 🚀

