# Karos Form Exercise

Le Karos Form Exercise est un petit exercice d'intégration d'un formulaire en Vue.js. Ce repo servira de template pour la suite de l'exercice.
L'enjeux de ce défi est de créer un formulaire constitué de plusieurs champs. Il doit répondre aux contraintes techniques listé plus bas, mais il doit aussi faire preuve de créativité en matière d'expérience utilisateur.


## Exercice

Pour cet exercice vous devrez donc intégrer 6 champs input d'un formulaire Html, ainsi qu'un bouton qui vérifie les champs et effectue un `console.log()` de ces valeurs.
Voici les différents champs à intégrer :

##### Name

Ce champ est un input de text, il ne doit pas dépasser 30 caractères.

##### Email

Ce champ est un input de text, il contient une adresse email. Cette adresse doit être validé par une regex.

##### Password

Ce champ est un input de password, il doit renvoyé le password sous forme de hashcode au format MD5

##### Date

Ce champ est un input de date, la date renvoyé doit être au format ISO.

##### Actif

Ce champ est une checkbox, il renvoi un boolean.

##### Country
Ce champ est une liste déroulante. Permettre le choix parmi 3 ou 4 pays max


Une fois le formulaire remplis, lorsque je clique sur le bouton, le `console.log()` devrait ressembler à ça :
```json
{
  "name": "Arthur",
  "email": "donotreply@karos.fr",
  "password": "3ceb0488d35fd725c0e643d1d58a965b",
  "date": "2018-08-08T12:57:21.343Z",
  "actif": true,
  "country": "france"
}
```

### Bonus

Afficher l'output du `console.log()` directement sur la page mis en forme dans un élément HTML.

### Bonus 2

Ajouter une config webpack au template.

## Ressources:

Pour vous aidez dans l'exercice je vous conseils de vous appuyer sur ces liens :

[Vue.js](https://vuejs.org/v2/guide/)

[Ux Design For Form](https://uxdesign.cc/design-better-forms-96fadca0f49c)

###### Faites vous plaisir et n'y passez pas trop de temps non plus 🙂 !
