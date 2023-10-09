# Projet : Analyse exploratoire et prédiction d'anomalies sur les arbres

## Présentation
Ce dépôt a pour objet l'étude et la prédiction des anomalies pouvant affecter les arbres. Il se base sur une analyse exploratoire approfondie des données relatives à ces derniers.

## Contenu du dépôt

1. **Analyse exploratoire des données**:
   - Compréhension des différentes caractéristiques des arbres : année de plantation, diamètre, espèce, genre botanique, stade de développement, vigueur, etc.
   - Visualisations mettant en exergue les relations entre certaines variables et la présence d'anomalies.
   
2. **Prétraitement des données**:
   - Conversion des types de certaines variables.
   - Suppression des variables redondantes ou peu pertinentes.
   - Gestion des données manquantes.

3. **Prédiction uni-label**:
   - Classification pour prédire la présence ou l'absence d'anomalies dans les arbres.
   - Comparaison de différents modèles : Random Forest, AdaBoost, SVM, KNN, et XGBoost.
   - Evaluation à l'aide de diverses métriques : précision, rappel, accuracy, etc.
   - Visualisation de l'importance des variables.

4. **Prédiction multi-label**:
   - Approche permettant de prédire plusieurs types d'anomalies pour un arbre donné.
   - Comparaison des performances des modèles sur ce problème plus complexe.

5. **Visualisation sur une carte**:
   - Répartition géographique des arbres et de leurs anomalies sur une carte de Grenoble.

## Conclusion
Grâce à cette étude, nous sommes en mesure d'identifier les caractéristiques importantes qui influencent la santé des arbres. Les modèles prédictifs développés permettent d'anticiper les anomalies potentielles, offrant une base solide pour des interventions proactives dans la gestion du parc.

