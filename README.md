# Projet 8 : Déployez un modèle dans le cloud

Un notebook en Pyspark exécutable avec kernel PySpark : 

   - chargement de 22 688 images stockées sur S3 (AWS)
   - preprocessing via la fonction preprocess_input de MobileNetV2
   - feature extraction via l'avant-dernière couche de MobileNetV2 SANS ENTRAINEMENT (Transfer learning)
   - réduction de dimension de type PCA
   - télécharger les features extraites/réduites au format .csv directement sur S3
