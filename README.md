
# Bootstrap et Modèles de Régression

## Introduction

Les méthodes classiques d'inférence statistique, comme le test t de Student ou le calcul d'intervalles de confiance, reposent sur des conditions d'application strictes. Ces méthodes supposent souvent que les populations-parents sont normales et que les échantillons sont aléatoires et simples. Cependant, en pratique, ces conditions sont souvent violées, ce qui limite l'efficacité de ces méthodes.

Pour résoudre ce problème, deux approches principales sont possibles :
1. Utiliser les méthodes classiques malgré la non-conformité aux conditions, en se basant sur la robustesse de ces méthodes.
2. Adopter des méthodes non paramétriques, moins restrictives.

## Le Bootstrap

Le bootstrap est une méthode d'inférence statistique qui exploite la puissance de calcul des ordinateurs modernes. Le terme "bootstrap" vient de l'expression anglaise “to pull oneself up by one’s bootstraps”, suggérant une méthode autonome et versatile. Le principe général du bootstrap est de rééchantillonner de nombreuses fois un échantillon initial pour réaliser l'inférence statistique sur les échantillons ainsi obtenus.

## Objectifs du Projet

Ce projet explore l'association entre le bootstrap et la régression linéaire. Nous examinerons comment le bootstrap peut être utilisé pour améliorer la robustesse et la fiabilité des modèles de régression linéaire, surtout lorsque les hypothèses classiques de la régression linéaire ne sont pas respectées. Nous couvrirons :
- Les méthodes de bootstrap (paramétrique et non paramétrique).
- L'application pratique du bootstrap en régression linéaire.

## Méthodologie

1. **Présentation des Méthodes :**
   - Introduction au bootstrap.
   - Concepts de base de la régression linéaire.
   - Utilisation du bootstrap en régression linéaire.

2. **Application Pratique :**
   - Illustrations et exemples concrets de l'utilisation du bootstrap pour améliorer les modèles de régression linéaire.

## Conclusion

Ce projet montre comment les techniques de bootstrap peuvent renforcer les modèles de régression linéaire en offrant des alternatives robustes lorsque les conditions d'application classiques ne sont pas respectées. Cependant, nos résultats ont également révélé que le bootstrap n’est pas toujours efficace, notamment dans des situations complexes. Par exemple, dans la régression multiple avec un nombre élevé de covariables par rapport au nombre d’observations, ou lorsque les erreurs du modèle sont hétéroscédastiques et que l’hétéroscédasticité ne peut pas être correctement modélisée.
