# Codes-pour-memoire
Ces fichiers contiennent l'ensemble des codes utilisés ainsi que les données au cours de ce mémoire 
# Modélisation de la volatilité financière par les modèles GARCH GARCH-TVE

Ce dépôt contient les codes R développés dans le cadre de mon mémoire de Master,
consacré à la modélisation de la volatilité des rendements financiers à l’aide
des modèles GARCH avec variables exogènes (GARCH-X) et de l’approche GARCH-EVT.

L’étude intègre l’écart absolu des rendements comme variable explicative de la
variance conditionnelle afin d’améliorer la modélisation de la volatilité.
Les événements extrêmes sont ensuite analysés à l’aide de la théorie des valeurs
extrêmes (Extreme Value Theory – EVT), selon la méthode Peaks Over Threshold (POT)

## Objectifs de l’étude

- Modéliser la volatilité conditionnelle des rendements financiers
- Évaluer l’apport de l’écart absolu des rendements comme variable exogène
- Capturer les comportements extrêmes des rendements
- Estimer des mesures de risque telles que le Value-at-Risk (VaR) et l’Expected Shortfall (ES)

## Données

Les données utilisées sont des séries temporelles financières (prix ou rendements).
Les rendements logarithmiques sont calculés à partir des prix de clôture.

Selon le cas, les données peuvent être :
- publiques, ou
- fournies à titre illustratif pour assurer la reproductibilité du code.

## Méthodologie

La démarche méthodologique suivie est la suivante :

1. Calcul des rendements logarithmiques
2. Construction de l’écart absolu des rendements comme variable exogène
3. Estimation d’un modèle GARCH(1,1) et de ses extensions avec variable exogène
4. Analyse des diagnostics et des résidus standardisés
5. Application de la méthode Peaks Over Threshold (POT)
6. Ajustement d’une loi de Pareto généralisée (GPD)
7. Estimation du Value-at-Risk (VaR) et de l’Expected Shortfall (ES)
8. Backtesting de la VaR et de l'ES
9. Validation croisée pour vérifier la robustesse hors échantillon
10. Analyse avant/après COVID-19
11. Estimation séparée des modèles
12. Tests de rupture 


Khadididiatou Sall
Université Iba Der Thiam de Thiès
Mémoire de Master

