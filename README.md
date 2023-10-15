### Classification d'images sur les handwritten digits

Dans ce projet, nous avons créé un modèle de classification des chiffres manuscrits en utilisant des algorithmes d'apprentissage non supervis avec comme jeu de données les digits issus de sklearn.datasets.
![img](./screenshots/images.png)
Pour celà nous procédons comme suit:
- Nous utilisons l'ACP (Analyse en Composantes Principales) pour réduire la dimension de nos images
![img](./screenshots/acp.png)
- Détermination du nombre de clusters avec la méthode du coude
![img](./screenshots/elbow.png)
- Clustering avec Kmeans
<table>
<tr>
<th>Visualisation</th>
<th><Métriques/th>
</tr>
<tr>
<td><img src="./screenshots/Kmeans1.png"/></td>
<td><img src="./screenshots/Kmeans.png"/></td>
</tr>
</table>
- Clustering avec Gaussian Mixture
<table>
<tr>
<th>Visualisation</th>
<th>Métriques</th>
</tr>
<tr>
<td><img src="./screenshots/GMM.png"/></td>
<td><img src="./screenshots/GMM1.png"/></td>
</tr>
</table>

### Test sur interface graphique

![img](./screenshots/gui.png)
![img](./screenshots/test2.png)
![img](./screenshots/test3.png)
![img](./screenshots/test4.png)
![img](./screenshots/test5.png)



Le clustering, en plus d'être un apprentissage automatique non supervisé, peut également être utilisé pour créer des clusters en tant que fonctionnalités permettant d'améliorer les modèles de classification. À eux seuls, ils ne suffisent pas pour la classification, comme le montrent les résultats. Mais lorsqu'elles sont utilisées comme fonctionnalités, elles améliorent la précision du modèle.
Vous pourrez voir les résultats de cette utilisation au niveau du notebook *Classification_Sur_Handwritten_Digits.ipynb*.