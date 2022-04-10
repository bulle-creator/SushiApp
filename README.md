# SushiFast
Groupe: Eva  
Date: Vendredi 10 Décembre 2021

## Contexte

Cette situation professionnelle repose sur le développement d’une application Front-end avec le framework Angular pour une prise de commande au niveau d’un point de vente. Deux scénarios peuvent coexister : l’opérateur prend la commande par téléphone pour une livraison à domicile ou le serveur prend une commande pour une consommation sur place. On comprend bien pourquoi, étant une application interne, il n’existe pas d’authentification pour l’instant. Elle utilisera par ailleurs une application Back-end dans le cadre d’une API présentant la gamme de produits à la vente. On se base sur les SushiBoxes de l’entreprise SushiShop afin d’approcher le plus une réalité commerciale.

## Utilisation d'une API pour Angular

Lors de ce projet, je vais devoir utiliser une base de donnée donc devoir relier mon projet angulard à mon API.  
En utilisant :
```
 res.setHeader('Acces-Control-Allow-Origin','*')
```
Pour pouvoir utiliser la base de donnée dans mon projet angulard, j'ai créer un service 
```
ng generate service services/projetangulard
```
Ensuite j'ai utiliser tout les informations qui sont dans la base de donnée:
```
<td>{{sushiapi[0].nom}}</td><br>
<td> Prix :{{sushiapi[0].prix}}</td> <br>
<td>Piéces :{{sushiapi[0].pieces}}</td><br>
```

## Réglement Général sur la Protection des Données  
Dans mon Rgpd il y aurait mon nom, prenom, la forme juridique, mon numero de SIRET, mon adresse postal. Les information pour me contacte (email et telephone)
et mon hébergeur(et un lien vers la cnil).
Je vais aussi devoir explique aux utilisateur la finalité de cette collecte de donné et leur rapeller le droit d'utilisateur.

#Evil User Story

En tant qu'utilisateur malveillant je souhaite avoir accés à la base de donné afin modifier le contenue de l'application web.




