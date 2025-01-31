# Projet de Machine Learning et Optimisation

## Introduction

Ce projet explore la relation entre le taux d'apprentissage et la taille des batches dans l'entraînement de modèles d'apprentissage profond. L'objectif est d'optimiser la performance des modèles, réduire le temps d'entraînement et améliorer la généralisation.

## Contexte

Dans l'entraînement des modèles, deux hyperparamètres cruciaux sont le taux d'apprentissage et la taille des batches. Un ajustement approprié de ces paramètres peut significativement influencer la précision, la vitesse de convergence et la généralisation des modèles.

## Méthodologie

1. **Jeux de données** : 
   - MNIST
   - CIFAR-10

2. **Modèles** :
   - Réseau de neurones convolutifs (CNN)
   - Wide ResNet

3. **Paramètres testés** :
   - Taux d'apprentissage : 1e-6, 1e-4, 1e-2, 1e-1
   - Tailles de batch : 32, 64, 128, 256 pour la première méthode
   - Tailles de batch : 128, 256, 512 pour la seconde méthode

4. **Approche** :
   - Recherche par grille (Grid Search) pour évaluer différentes combinaisons de paramètres.
   - Entraînement des modèles sur plusieurs époques et évaluation de leur performance.

## Résultats

Les résultats montrent que :
- Un taux d'apprentissage de 0.001 et 0.01 est le plus efficace pour le modèle sur le jeu de données CIFAR-10, atteignant des précisions d'environ 64-65%.
- Une taille de batch plus grande peut nuire à la précision, tandis que des tailles plus petites favorisent un meilleur apprentissage.

## Conclusion

Cette étude met en évidence l'importance du taux d'apprentissage et de la taille des batches dans l'entraînement des modèles d'apprentissage. Un bon choix de taux d'apprentissage est crucial pour maximiser l'efficacité de l'entraînement.

## Références

- Smith, L. N., & Le, Q. V. (2018). Don't Decay the Learning Rate, Increase the Batch Size. Proceedings of the 35th International Conference on Machine Learning.
- Goyal, P., Dollár, P., Girshick, R., & Farhadi, A. (2017). Accurate, Large Minibatch SGD: Theory and Practice. arXiv preprint arXiv:1706.02677.

## Contact

Pour toute question ou contribution, veuillez contacter :
- **IGNASSOU Kadi**
- **MISSENGUE MOULOMBO Exaucée**
- Sous la supervision de Mme. MBIA NDI Marie Thérèse, Enseignante à l'ISSEA.
