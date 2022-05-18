# project_DevOps

## Tests unitaires
Ils permettent de tester une partie de notre programme. Ici, Jest est utilisé pour testé son app.
Ils sont effectué à chaque push.

## Tests de sécurité
Trivy effectue des tests de securité puis envois tout dans l'onglet Security de github.
Ils sont effectué à chaque push.

## Difficultés
J'ai voulu utiliser Docker et build une image, cependant, je n'ai pas réussi à deployer correctement l'image.

## Differents deploiements possible
Pour deployer une image Docker, il existe 3 solutions, Azure, AWS et Kubernetes si j'ai bien compris.
Sans utiliser Docker, on peut utiliser des solutions gratuites comme Firebase ou Heroku.
