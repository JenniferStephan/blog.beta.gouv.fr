---
layout: post
title: "Les bénéfices de l'approche produit : Coup de projecteur sur Mes Aides"
date: 2019-11-17
authors:
  - thomas.guillet
categories: general
tags:
excerpt: >-
  Florilèges d'améliorations plus ou moins inattendues qui nous ont permis d'augmenter notre impact sans augmenter la taille de l'équipe !
---





## L'obsession de l'amélioration continue

Au sein du collectif [beta.gouv.fr](https://beta.gouv.fr), nous déclinons l'[obsession du service client](https://medium.com/@djo/obsession-service-client-captain-train-cb0b91467fd9) pour améliorer la qualité des services publics numériques que nous développons.


## Nos 3 recommandations

### Ouvrez les canaux de communication

Notre email de contact est [omniprésent](https://github.com/betagouv/mes-aides-ui/search?q=mail-to&unscoped_q=mail-to) sur les pages du simulateur. Nous avons aussi mis en place un [compte Twitter](https://twitter.com/mesaides) et une [page Facebook](https://www.facebook.com/MesAides) pour être facilement joignable.

### Rencontrez les personnes



### Mesurez (anonymement) les usages



## En pratique sur [mes-aides.gouv.fr](https://mes-aides.gouv.fr)


### Une page dédié pour le traffic provenant d'ameli.fr

> Constat : 33% du traffic de Mes Aides provient d'ameli.fr et ce traffic génère de nombreuses sollicitations par email.

Les personnes arrivent sur le simulateur avec un problème précis en tête. Pour la plupart d'entre elles, elle ne cherchent pas à faire une simulation.

Pour leur apporter une information pertinente sans surcharger la page d'accueil, ces personnes sont automatiquement redirigées vers [une page dédiée](https://mes-aides.gouv.fr/ameli) dans laquelle nous avons compilé les réponses aux problèmes les plus fréquents.

Avec cette modification, nous évitons aux usagers de se lancer dans une simulation qui ne va pas leur apporter les informations que recherchent et nous diminuons le nombre de courriels à traiter par l'équipe !

### Une page de résultats enrichie pour ce traffic

> Constat : Malgré cette page intermédiaire, des sollicitations continuent d'arriver au sujet de l'éligibilité aux dispositifs de l'assurance maladie (CMU-C, ACS et plus récemment la CSS).

Une partie du flux provenant d'ameli.fr cherche bien à savoir si elle est éligible à des prestations sociales et en particulier à la Couverture maladie universelle complémentaire (CMU-C), l'Aide au paiement d’une complémentaire santé (ACS) et la Complémentaire santé solidaire (CSS).

Pour ces personnes provenant d'ameli.fr, nous avons ajouté une section à la page de résultats qui permet d'expliciter la non-éligiblité à ces trois prestations en fonction des résultats du simulateur. En effet, le parti pris sur Mes Aides était de limiter l'information affichée et de n'afficher que les prestations auxquelles les personnes semblent éligibles.


### « Êtes-vous propriétaire de votre logement principal ou bien logé gratuitement ? »

> Constat : Cette question, extraite du [simulateur de la prime d'activité sur caf.fr](http://www.caf.fr/allocataires/mes-services-en-ligne/estimer-vos-droits/simulation-prime-d-activite), est à l'origine de nombreux signalements d'écart entre les deux simulateurs.

Il faut répondre « Non » lorsque vous êtes toujours en train de rembourser le crédit pour votre logement principal ou si vous êtes hébergé en participant aux frais du logement. C'est d'ailleurs ce qui est précisé dans une infobulle près de la question mais celle-ci n'est pas utilisée en pratique.

Pour les personnes dans ces situations, lorsqu'elles apparaissent éligibles à la prime d'activité, un lien supplémentaire avec la mention « montant inattendu » leur est proposé près du montant estimé. Ce lien leur permet d'accéder à une page sur laquelle nous explicitons la différence d'interprétation à l'origine de l'écart.

En octobre 2019, 650 personnes ont cliqué sur ce lien. Informées, ces personnes n'ont pas eu à nous contacter.


### Rendre plus actionnable la page de résultats

> 


### Plus d'options pour lancer les démarches

> « Afficher le lien pour les démarches en ligne c'est bien mais, s'il vous plaît, conservez les liens vers les alternatives papier quand elles existent ! »

Cette remarque nous a été faits lors d'une rencontre de travailleurs sociaux dans l'Ardèche en début d'année. L'assistante sociale qui nous a interpellés accompagne des personnes âgées ; démunies lorsqu'elles doivent faire leurs démarches en ligne mais tout à fait autonomes quand il s'agit de remplir un formulaire papier.

Nous avons affiché les alternatives sur la page de résultats pour que les personnes puissent choisir celle qu'elle préfèrent. Lorsque le téléservice et le formulaire sont affichés environ 15% des personnes choississent le formulaire !

Avec le même objectif, nous avons ajoutons des liens vers des lieux d'accueil physique où les personnes peuvent se rendre pour être accompagner et faire leurs démarches. Pour l'allocation de solidarité aux personnes âgées, environ 10% des personnes choississent d'afficher la liste de ces lieux.

