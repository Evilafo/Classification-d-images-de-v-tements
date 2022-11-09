# Classification-d-images-de-v-tements
### Ce Notebook forme un modèle de réseau de neurone pour classer les images de vêtements, comme les baskets et les chemises.
Les modèles de classification d'images ont des millions de paramètres. Les former à partir de zéro nécessite beaucoup de données de formation étiquetées et beaucoup de puissance de calcul. L'apprentissage par transfert est une technique qui raccourcit une grande partie de cela en prenant un morceau d'un modèle qui a déjà été formé sur une tâche connexe et en le réutilisant dans un nouveau modèle.

Ce Notebook montre comment créer un modèle Keras pour classer cinq espèces de fleurs à l'aide d'un modèle pré-entraîné TF2 SavedModel de TensorFlow Hub pour l'extraction de caractéristiques d'image, entraîné sur l'ensemble de données ImageNet beaucoup plus grand et plus général. En option, l'extracteur de caractéristiques peut être entraîné ("affiné") avec le classificateur nouvellement ajouté.
