## Segmentation des ventes de Livres d'une chaîne de Librairie

# Contexte

Afin de mieux connaitre et comprendre sa clientèle, une chaîne de librairie souhaite éffectuer une segmentation de ses ventes de livres durant l'année écoulée en fonction de leurs catégories et/ou des auteurs qui les ont rédigé. Les responsables de la chaîne souhaitent repondre aux questions métier suivantes pour chaque segment (Catégorie du livre et/ou auteur):

**-** Quel est le nombre des ventes dans l'année ? 

**-** Quel est le nombre des ventes mensuelles ? 

**-** Quel est le montant des ventes dans l'année ? 

**-** Quel est le montant des ventes mensuelles ? 

**-** Quel est le classement des 8 plus grandes ventes ? 

**-** Quel est le montant des ventes par ville ?

Au delà de la segmentation des ventes, les responsables de l'entreprise veulent savoir si leurs objectifs de réaliser un chiffre d'affaire annuel de **6000 €**  a été atteint et **quels sont les modes de paiement utilisés par les clients**.


# Méthodologie

**-** Connexion de Power Bi à la source de données (Notre source de données est une base de données Access contenant des informations sur les clients, les commandes, les livres, les modes de paiement, les vendeurs)

**-** Prétraitement des données dans PowerQuery (Vérification du format des données, gestion des données manquantes)

**-** Création du Data Model en établissant les relations existantes entre les tables 

**-** Création de nouvelles mesures ou indicateurs avec le langage Dax

# Résultats

En premier lieu, il est important de constater à travers la **KPI** de vente annuel qui est sous forme de jauge, que l'objectif de ventes annuel de **6000 €** n'a pas été atteint. La différence entre le montant de vente réalisé et l'objectif est de l'odre de **€ 1,75 K**.

La réponse aux questions métiers citées plus haut dans la partie **contexte** dépendrons de la catégorie du livre considéré et/ou de l'auteur du livre. Par exemple, pour la catégorie de livres **Bande Déssiné**, il y'a eu au cours de l'année **9 ouvrages** vendus pour un montant total de **61,74  €** avec un pic des ventes en Mai (5 ventes). Les villes où il y'a eu le plus de ventes sont respectivement **Bayonne, Montpelier, Ganges, Lyon et Perpignan**. 










