# Infini pour Deppo

Une extension de fonctionalité pour charger la fonte Infini, et désactiver la fonte originale du thème Deppo ([HK Grotesk](https://hanken.co/product/hk-grotesk/), par Alfredo Marco Pradil).

Note: il serait assez simple de charger cette fonte sans extension, en ajoutant simplement deux lignes dans votre CSS additionnel:

```css
@import 'http://www.cnap.graphismeenfrance.fr/infini/css/infini-fontes.css';
body { font-family: 'Infini', sans-serif; }
```

Cependant, en faisant ça on ne désactive pas pour autant la fonte par défaut du thème, qui équivaut à 5 connexions http et environ 100kb dont on pourrait se passer.

C'est ce que fait ce plugin, qui désactive la fonte par défaut du thème Deppo.

***

Cette extension a été développée dans le cadre du [cours Programmation Web](https://cours-web.ch/) à l'Eracom.