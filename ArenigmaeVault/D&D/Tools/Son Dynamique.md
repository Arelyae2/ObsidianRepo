Pour l'outil de **Son Dyanmique**, on y mettrait:


## Events d'Ambiance

Les events d'ambiance sont classés en plusieurs, catégories, plusieurs events d'une même, catégorie ne peuvent exister en même temps, mais toutes les catégories sont toujours lancés en même temps.

- Environnement Principal (De la pluie, du vent...)
- Environnement Secondaire (La nature, les bruits de la ville)

En même temps sont lancés des séries de son de manière aléatoire en accord avec l'environnement secondaire (paramètre Fmod).

Les catégories sont diégétiques et sont définis en zone avec la [[Map interactive]]

## Events de Musique

[Musique de Combat](https://www.youtube.com/watch?v=05gND_E22dA&list=PL675rrCEB6bjKWeF0nyogFWq11MlOc8jf&index=7)

Les events de musique définissent différents états de jeu.
Aucun de ces état ne peut exister en même temp qu'un autre

Les events peuvent être défini selon plusieurs choses:
Un event de **Zone**, les events de **Zone** sont défini la ou la caméra regarde dans [[Map interactive]], ils ne sont pas spatialisés mais défini par des zones dans l'éditeur, et peuvent transitionner de l'un à l'autre avec un paramètre commun.

Un event *Override* qui outrepasse la dite **Zone**, les events *Override* s'applique en général pendant les combats ou les évènements importants.

Un event *Override* n'est arrêté que lorsqu'on lui dit, un event de **Zone** ne peut pas arrêter un autre event *Override*, sinon il devient lui même un *Override*


La liste suivante est non exhaustive
### Défaut 
**Zone**
Par défaut, une musique d'ambiance si jamais aucun autre état n'est référencé.

### Village
**Zone**
Une musique de village simple représentant le mood de celui-ci, elle doit pouvoir switcher d'ambiance une fois en intérieur.

### Ville
**Zone**
Similaire au village mais beaucoup plus chargé, comme la ville, il y a du monde. Tous comme le village également, elle doit pouvoir switch une fois en intérieur.

### Nature
**Zone**
Musique calme transmettant le mood de l'endroit 
### Donjon
**Zone**
Musique servant soit a la refléxion, soit a l'exploration, un volume d'intensité nécessaire pour permettre aux joueurs de réfléchir plus calmement et enlever des instruments.

### Combat
*Override*
Le combat commence par une intro avant d'aller sur une loop, puis une fois fini, vas vers une intro, et revient a l'event de **Zone** dans lequel les joueurs sont.
Cet event en contient un autre, le climax de combat, qui lance une partie plus héroïque de la musique avant de revenir sur la loop normal
#### Musiques de combat normal
Combat Variation 1
![[CombatVariation1.mp3]]

Combat Variation 2
![[CombatVariation2.mp3]]

Combat Variation 3
![[CombatVariation3.mp3]]

Combat Variation 4
![[CombatVariation4.mp3]]

Combat Variation 5
![[CombatVariation5.mp3]]

#### Musiques de combat climax

Climax 1
![[Climax1.mp3]]

Climax 2_3
![[Climax2_3.mp3]]

Climax 4_5
![[Climax4_5.mp3]]


### Voyage
*Override*
Lorsque les joueurs vont voyager, une musique d'aventure qui permet de transitionner naturellement entre deux zones très différentes.

### Musique diégétique
*Override*
Dans le cas d'un barde jouant sa musique ou d'un orchestre dans un bar, c'est un endroit spatialisé, le plus rapproché, le plus bas la musique de zone est.

## Relation avec [[Map interactive]]




