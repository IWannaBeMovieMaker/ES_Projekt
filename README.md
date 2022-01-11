# ES_Projekt
Projekt se zabývá problematikou vyhledávání ve Wordpressu, hlavní částí projektu je ElasticSearch, jenž hostuje plugin ElasticPress. Ten nahrazuje jisté nedostatky Wordpressu jako je například rychlost či zátěž webu a dodává spravované stránce řadu možností pro vyhledávání, díky funkcím jimiž disponuje.
## Využité technologie a jejich využití
#### Docker
* slouží pro vytvoření jednotného rozhraní pro odlišné kontejnery
* výhodami jsou multiplatformnost a menší velikost
#### WordPress
* slouží pro vytvoření a úpravu webu
#### ElasticSearch
* fulltextový vyhledávač, po integraci s WP vylepšuje jeho rychlost a také na sebe bere zatížení vyvolané vyhledáváním
#### Kibana
* Vizualizace dat ElasticSearche
* Grafy a logy
* Vývojářské nástroje - možnost testování funkcí ES pomocí Query (dotazů)
#### phpMyAdmin
* slouží pro rychlou správu WP databáze
## Porty jednotlivých kontejnerů
*localhost:[port]*
* WordPress :80
* ElasticSearch :9200
* Kibana  :5601
* phpMyAdmin  :8070

### Využité pluginy
##### ElasticPress
* EP ve WordPressu vylepšuje funkčnost vyhledávání
* Díky funkcím tohoto pluginu je možné si vyhledávání nastavit dle libosti
##### WooCommerce
* Slouží k vytvoření funkčního e-shopu zdarma
* Má i placené části, které však nejsou potřeba (předplatné)
