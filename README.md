# Classification d'images de vêtements
### Ce Notebook forme un modèle de réseau de neurone pour classer les images de vêtements, comme les baskets et les chemises.
Les modèles de classification d'images ont des millions de paramètres. Les former à partir de zéro nécessite beaucoup de données de formation étiquetées et beaucoup de puissance de calcul.

Ce Notebook forme un modèle de réseau de neurone pour classer les images de vêtements, comme les baskets et les chemises.
Ce Notebook utilise tf.keras , une API de haut niveau pour créer et former des modèles dans TensorFlow.


## Préambule
Pour ce projet, les données ont été manipulées en Python sur support Jupyter Notebook avec développement. Google Colab a été utilisé pour l'entraînement du modèle en exécution GPU.

### Les données
 Ce guide utilise le jeu de données Fashion MNIST qui contient 70 000 images en niveaux de gris dans 10 catégories. Les images montrent des vêtements individuels à basse résolution (28 par 28 pixels)


## Prérequis techniques
Si vous n'avez jamais installé **Python**, alors autant installer directement la **distribution Anaconda**.
Anaconda est donc une distribution Python, faite pour la Data Science.

De cette manière on peut installer Python et ses librairies de Data Science Pandas, Matplotlib, Seaborn, Scipy, Numpy etc… 
Mais aussi le notebook Jupyter, qui reste incontournable et vivement recommandé!
C'est par ici : [Anaconda](https://www.anaconda.com/download)

Si vous souhaitez lancer le projet, il sera nécessaire d'installer Jupyter Notebook sur votre mahcine. 
La doc. Jupyter est accessible via : [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/install.html) 

```
python -m pip install --upgrade pip    
python -m pip install jupyter
```

Pour tester l'installation, vous pouvez taper dans votre console la commande suivante :

```
jupyter notebook
```

### Installation des principales librairies Python uniquement
*Pour installer python ainsi que les librairies de Data Science, il est fortement recommandé d'installer la distribution Anaconda.* 

```
pip install pandas
pip install matplotlib
pip install numpy
pip install scipy
```

## Auteur

**Evilafo** *(Emmanuel Evilafo)* [Persona](https://evilafo.xyz) - *Initial work* - [Github](https://github.com/Evilafo)
