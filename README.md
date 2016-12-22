# Trophy Logbook – Un Journal Jekyll

cf le post de contexte : [Journaling with Jekyll](https://medium.com/@craigeley/journaling-with-jekyll-c7065031a33#.9v9e9vq5p)

![](https://raw.githubusercontent.com/craigeley/trophy-logbook/master/_screenshots/individual_entry.png)

Une variante du thème Jekyll [Trophy](https://github.com/thomasvaeth/trophy-jekyll) conçue pour être utilisée comme un journal de bord personnel. Basé sur une plateforme de blog, il utilise quelques-unes des fonctionnalités de Jekyll de manière vraiment peu-standards. 

Si vous ne connaissez pas Jekyll, vous en saurez un peu plus [ici](http://jekyllrb.com/docs/home/) ou en rejoigant la [communauté jamstatic](https://jamstatic.fr).

## Fonctionnalités 

- Les "tags" et catégories de Jekyll ont été bidouillés pour servir comme enregistrements de personnes et de lieux. Avec l'aide de [`jekyll archives`](https://github.com/jekyll/jekyll-archives), ceci permet la création automatique d'enregistrements qui répondent aux questions telles que "Combien de fois je suis vraiment allé au Social Bar cette année ?" ou "Quand ai-je dîner la dernière fois avec Barbara ?"
    + En outre, en utilisant le répertoire "_categories" de Trophy, vous pouvez créer une description et une image pour compléter ces entrées, tout comme sur un wiki. Ces entrées sont automatiquement mises à jour pou y ajouter les dates auxquelles vous avez visité un lieu ou rencontré une personne.
- Cartes statiques générées automatiquement en utilisant l'API Google Static Maps. Ajoutez simplemnet une adresse de rue ou les coordonnées lat/long pour n'importe quelle entrée.
    + Un niveau de zoom personnalisé si vous voulez voir la plus grande image.
- Extensibilité et flexibilité faciles - juste du plein-texte.

## "Fonctionnalités"
- L'utilisation de `jekyll-archives` pour la création automatique d'enregistrements de personnes et de lieux améliore *grandement* la fonctionnalité de ce projet. Cependant, cela le rend incompatible avec [GitHub Pages](https://pages.github.com/). Vous pouvez consulter le repo d'origine [Trophy] (https://github.com/thomasvaeth/trophy-jekyll) pour une solution compatible Pages.

## Structure du site

À partir de l'écran d'accueil, les éléments les plus visibles sont les «jours» :

![](https://raw.githubusercontent.com/craigeley/trophy-logbook/master/_screenshots/homepage.png)

Les jours sont composés d'entrées individuelles, qui sont les messages contenus dans le dossier `_posts`:
! [] (Https://raw.githubusercontent.com/craigeley/trophy-logbook/master/_screenshots/summarized_day.png)

Les posts peuvent éventuellement contenir des enregistrements de gens et de personnes, qui créent leurs propres entrées. Par défaut, ces entrées ne contiennent qu'une liste de tous les jours pour lesquels elles sont entrées. Cependant, en créant un fichier sidecar dans le dossier `_categories`, vous pouvez inclure des métadonnées telles qu'une image et une description. Ces fichiers doivent utiliser un tiret au lieu d'un espace dans leur nom. Voir [le dossier _categories] (https://github.com/craigeley/trophy-logbook/tree/master/_categories) pour des exemples, comme celui-ci:


![](https://raw.githubusercontent.com/craigeley/trophy-logbook/master/_screenshots/location_entry.png)

## Attention 

N'hésitez pas à laisser des commentaires et/ou envoyer vos "pull-requests" pour des bugs évidents, et je ferai de mon mieux. Pour des choses comme les demandes de fonctionnalités majeures ou la modification du fonctionnement du site, je suggère de creuser autour dans le code et voir si vous pouvez le faire vous-même. En un sens, ce projet est fourni «tel quel».

## Licence
Trophy Jekyll licencié sous la Licence MIT.