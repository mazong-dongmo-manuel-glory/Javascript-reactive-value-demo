# Javascript-reactive-value-demo
🚀 #Frameworks réactifs pour les devs! 🤯 Les valeurs réactives sont omniprésentes en développement #web, mais comment ça marche vraiment ? Voici une démo simplifiée pour montrer que ce n'est pas si complexe 🧵
# Framework Réactif Simplifié en JavaScript

Ce dépôt contient un exemple simple d'un framework réactif en JavaScript, destiné à expliquer comment les valeurs réactives fonctionnent dans les frameworks modernes.

## Comment ça fonctionne

Dans ce projet, nous avons créé une structure de base d'un framework réactif en utilisant JavaScript. Voici comment cela fonctionne :

1. **`watcher`** : Une fonction qui enregistre la fonction actuellement en cours d'utilisation. Cette fonction est appelée à chaque modification de la valeur réactive.

2. **`Reactive`** : Une classe qui permet de créer des valeurs réactives. Elle possède un getter et un setter pour gérer la réactivité. Le getter enregistre la fonction actuelle (si une fonction l'utilise), puis renvoie la valeur réactive. Le setter met à jour la valeur réactive et exécute toutes les fonctions enregistrées.

3. **Mise en Application** : Dans l'exemple fourni, nous utilisons ce framework réactif pour créer un compteur réactif. Une fonction est enregistrée pour mettre à jour un élément HTML avec l'ID "app" chaque fois que la valeur réactive change.

## Pourquoi c'est important

Les frameworks réactifs modernes, tels que Vue.js, React et Angular, reposent sur des concepts similaires pour rendre les applications web réactives aux changements de données. Comprendre ces concepts fondamentaux est essentiel pour le développement web moderne.

N'hésitez pas à explorer ce dépôt pour voir comment tout cela fonctionne. Il peut être utile pour ceux qui souhaitent approfondir leur compréhension des valeurs réactives et de la réactivité dans le développement web.

