# projet 8, Réalisez un traitement dans un environnement Big Data sur le Cloud

# Testé AWS et Google Cloud
# Packages essentiels : pyspark, tensorflow

# Ce projet consiste à effectuer une extraction de feature + ACP,
# sur un dataset de 300 photos de fruits (131 catégories différentes).
# d'abord en local, puis sur le cloud.


# Ce dossier comporte :

1 Notebook AWS : 
    Le notebook réalisé par un alternant, complété (PCA). Première solution testée : AWS
    Rôle IAM, données stockées sur S3, créations d'instances EC2 avec bootstrap et persistance, tunnel SSH au maître + proxy.

2 Notebook Images
    Le notebook déployé sur le cloud. 
    Données stockées dans un bucket google storage. Possible de créer des instances depuis le Compute Engine,
    de manière très similaire à AWS. 
    Seconde solution, retenue : Vertex Workbench, puisqu'on travaille depuis un notebook. Environnement choisi : pyspark
    (sinon, il faut installer Java !)
    
3 Présentation
