# Objectif
En France, la transformation culturelle du pays est un sujet tabou depuis de nombreuses années. Pourtant, il serait relativement simple de confirmer ou d'infirmer l'hypothèse selon laquelle la France subit une transformation culturelle significative. En effet, si celle-ci existe, alors elle devrait nécessairement se répercuter sur l'origine des prénoms donnés aux nouveaux nés. Nous avons donc pris parti de mesurer cette éventuelle transformation en trackant la part des prénoms d'origine diverses donnés depuis les années 70. Si la part des prénoms traditionnels (prénoms du calendrier) tend à baiser significativement avec les années tandis que la part des prénoms d'origine X ou Y tend à augmenter significativement alors nous pourrons déduire formellement que la France subit une transformation culturelle.

# Données & Preprocessing
* La fréquence des prénoms donnés aux nouveaux nés les 50 dernières années dans les différents départements français est disponible sur le site de l'INSEE : https://www.insee.fr/fr/statistiques/2540004
* Les accents sont supprimés
* Lowerisation des caractères

# Méthode
* Crawling de listings de prénoms de diverses origines sur le web
  * Calendrier Français
  * Prénoms bibliques
  * Prénoms hébraïques
  * Prénoms turcs
  * Prénoms arabes
  * Prénoms africains autre qu'arabes
  * Prénoms d'autres origines (entre autres via https://fr.wikipedia.org/wiki/Cat%C3%A9gorie:Liste_de_pr%C3%A9noms)
* Preprocessing : suppression des accents
* Preprocessing : lowerisation des caractères
* Matching des prénoms crawlés avec la database de l'INSEE

