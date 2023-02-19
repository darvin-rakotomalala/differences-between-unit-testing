## Tests unitaires vs tests d'intégration vs tests fonctionnels

Dans ce repo, nous allons voir les différences entre les tests unitaires, les tests d'intégration et les tests.

Pour toute application logicielle, les tests unitaires, ainsi que les tests d'intégration, sont très importants car chacun d'eux utilise un processus unique pour tester une application logicielle
Mais aucun ou même les deux ne peuvent remplacer les tests fonctionnels à aucun moment.
	
- **Test unitaire** signifie tester des modules individuels d'une application de manière isolée (sans aucune interaction avec les dépendances) pour confirmer que le code fait les choses correctement.
- **Test d'intégration** signifie vérifier si différents modules fonctionnent correctement lorsqu'ils sont combinés en tant que groupe.
- **Test fonctionel** signifie tester une partie des fonctionnalités du système (peut interagir avec les dépendances) pour confirmer que le code fait les bonnes choses.
	
Les tests fonctionnels sont liés aux tests d'intégration, cependant, ils signifient les tests qui vérifient la fonctionnalité de l'application entière avec tout le code en cours d'exécution, presque un test de super intégration.
	
*Les tests unitaires considèrent la vérification d'un seul composant du système, tandis que les tests de fonctionnalités envisagent de vérifier le fonctionnement d'une application par rapport aux fonctionnalités prévues décrites dans la spécification des exigences du système. D'autre part, les tests d'intégration considèrent la vérification des modules intégrés dans le système.*
	
Et surtout, pour optimiser le retour sur investissement (ROI), votre base de code doit avoir autant de tests unitaires que possible, moins de tests d'intégration et le moins de tests fonctionnels.
	
Ceci est illustré le mieux dans la pyramide de test suivante:
	
<IMG>
	
Les tests unitaires sont plus faciles à écrire et plus rapides à exécuter. Le temps et les efforts nécessaires pour implémenter et maintenir les tests augmentent entre les tests unitaires et les tests fonctionnels, comme indiqué dans la pyramide ci-dessus.
	
Par exemple : Pour un téléphone mobile fonctionnel, les principales pièces requises sont la « batterie» et la «carte sim ».
- **Exemple de test unitaire** - La batterie est vérifiée pour sa durée de vie, sa capacité et d'autres paramètres. La carte SIM est vérifiée pour son activation.
- **Exemple de test d'intégration** - La batterie et la carte SIM sont intégrées, c'est-à-dire assemblées pour démarrer le téléphone mobile.
- **Exemple de test fonctionnel** - La fonctionnalité d'un téléphone mobile est vérifiée en termes de fonctionnalités et d'utilisation de la batterie ainsi que des fonctionnalités de la carte SIM.

[Source d'article](https://fre.myservername.com/differences-between-unit-testing)