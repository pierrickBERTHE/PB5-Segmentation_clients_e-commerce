# <span style='background:blue'>Contexte</span>

**Olist** souhaite que nous fournissons à ses équipes d'e-commerce une segmentation des clients qu’elles pourront utiliser au quotidien pour leurs campagnes de communication.

Nous devons fournir à l’équipe Marketing une description actionnable de notre segmentation et de sa logique sous-jacente pour une utilisation optimale, ainsi qu’une proposition de contrat de maintenance basée sur une analyse de la stabilité des segments au cours du temps.


# <span style='background:blue'>Missions</span>

**Réaliser la segmentation des clients en utilisant des methodes non-supervisées**.

Notre objectif est de comprendre les différents types d’utilisateurs grâce à leur comportement et à leurs données personnelles. Pour cela nous devons :
1. Réaliser une courte analyse exploratoire.
2. Tester differents modèles de segmentation afin de repondre au mieux à la problematique.
3. Créer une proposition de contrat de maintenance basee sur une analyse de la stabilité des segments au cours du temps.


# <span style='background:blue'>Dataset</span>

Olist nous fournit une base de données anonymisées comportant des informations
sur l’historique de commandes, les produits achetés, les commentaires de
satisfaction, et la localisation des clients depuis janvier 2017.

Source : [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/olistbr/brazilian-ecommerce)<br>

9 fichiers CSV :
- olist_customers_dataset.csv
- olist_geolocation_dataset.csv
- olist_order_items_dataset.csv
- olist_order_payments_dataset.csv
- olist_order_reviews_dataset.csv
- olist_orders_dataset.csv
- olist_products_dataset.csv
- olist_sellers_dataset.csv
- product_category_name_translation.csv

Relations entre les fichiers CSV :
<br><br>
<img src="https://i.imgur.com/HRhd2Y0.png" width="800" height="500">


# <span style='background:blue'>Fichiers du dépôt</span>

- **Berthe_Pierrick_1_notebook_exploration_112023.ipynb** : Notebook de nettoyage, feature engineering et analyse exploratoire des données

- **Berthe_Pierrick_2_notebook_essais_112023.ipynb** : Notebook de modélisation de la segmentation des clients avec différents algorithmes de Machine learning non supervisés / clustering (K-Means, CAH, DBSCAN)

- **Berthe_Pierrick_3_notebook_simulation_112023.ipynb** : Notebook de simulation de la stabilité des segments de clustering au cours du temps pour émettre une proposition de contrat de maintenance

- **Berthe_Pierrick_4_presentation_112023.pdf** : Présentation des résultats


# <span style='background:blue'>Auteur</span>

Pierrick BERTHE<br>
Novembre 2023
