## Objectifs

Après cet exercice, vous devriez pouvoir:

Activez l'option `-p` pour créer des répertoires parent pour un répertoire donné. Appliquez l'option `-v` pour afficher chaque répertoire créé avec une commande `mkdir`.

## Exemple

Les commandes Unix ont une fonctionnalité par défaut, mais nous permettent également de fournir des paramètres facultatifs qui modifient le comportement de la commande. Une option est spécifiée après la commande:

`$ Mkdir -v usa / los-angeles`
Nous avons spécifié l'option `-v` lors de la création d'un sous-répertoire de / usa, qui renvoie le nom du répertoire que nous venons de créer. Nous pouvons également créer des répertoires parent en spécifiant une option:

`$ Mkdir -p japan / tokyo`
Si nous ne spécifions pas l'option `-p`, nous aurions reçu une erreur indiquant:

Mkdir: japan: Aucun fichier ou répertoire de ce type
Mais parce que nous avons passé une option `-p`, le répertoire / japan a été créé en même temps que son sous-répertoire tokyo /.

## Exercice

* Changez dans le répertoire parent de votre pays.
* Créez un nouveau répertoire de pays avec un sous-répertoire de ville utilisant l'option `-p`.
