# Social housing in Paris

## Données

Les données proviennent du RPLS 2014 (Répertoire des logements locatifs des bailleurs sociaux) auquel tous avons accès, sous réserve d'en faire la demande : http://www.statistiques.developpement-durable.gouv.fr/sources-methodes/enquete-nomenclature/1542/0/repertoire-logements-locatifs-bailleurs-sociaux-rpls.html

## Outils utilisés

* La librairie csvkit 0.9.1 pour manipuler les fichier (csvcut, csvjoin, etc.)
* Quelques sed 's/x/y/g'
* L'API de http://adresse.data.gouv.fr/ pour la géolocalistion des adresses
* Mapbox Studio pour la partie cartographie.

## Géolocalisation

* Le SCORE_GEO correspond à "l'indice de confiance" renvoyé par l'API de adresse.data.gouv.fr.
* Certaines adresses ont été redressées manuellement.

## A faire

* Faire le même travail sur les autres départements d'Ile de France.
* Permettre une représentation cartographique par type de financement (PLAI, PLUS, PLS, PLI)
* ...

## Autres

Aucune garantie d'exactitude quant au résulat final.
