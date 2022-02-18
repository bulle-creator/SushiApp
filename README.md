# SushiFast
Groupe: Eva  
Date: Vendredi 10 Décembre 2021

## Utilisation d'une API pour Angulard

Lors de ce projet je vais devoir utiliser une base de donné donc je vais devoir relier mon projet angulard à mon API.  
En utilisant :
```
 res.setHeader('Acces-Control-Allow-Origin','*')
```
Pour pouvoir utiliser les donnés dans la base de donnés dans mon projet angulard j'ai du crée un service 
```
ng generate service services/projetangulard
```
En suite j'ai utiliser tout les information qui sont dans la base de donné:
```
<td>{{sushiapi[0].nom}}</td><br>
<td> Prix :{{sushiapi[0].prix}}</td> <br>
<td>Piéces :{{sushiapi[0].pieces}}</td><br>
```

## Réglement Général sur la Protection des Données  
Dans mon Rgpd il y aurait mon nom, prenom, la forme juridique, mon numero de SIRET, mon adresse postal. Les information pour me contacte (email et telephone)
et mon hébergeur(et un lien vers la cnil).
Je vais aussi devoir explique aux utilisateur la finalité de cette collecte de donné et leur rapeller le droit d'utilisateur.
