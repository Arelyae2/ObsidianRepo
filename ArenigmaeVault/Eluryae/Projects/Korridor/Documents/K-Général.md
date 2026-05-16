
## Boucle de travail

8 semaines

3 semaines et une milestone (rien d'officiel mais du travail de recherche + éventuel proto)
Rendu le 7 juillet pour la prochaine milestone, 3 semaines après le stage

Les 3 premières sont de la recherches, de la mise en place, du proto
Puis du contenu, de l'intégration.

## Le Jeu
### Général

Intention: exprimer un propos sur l'histoire de france et l'apprendre au joueur, un rapprochement avec le monde actuel.
Une réhabilitation du monde médiéval comme premier monde moderne, des poches de modernités dans les centres urbains.
Essor de ces centres au 12-13ème siècle. 

Aujourd'hui; on pense que la rupture de la révolution est le début de la modernité.

La modernité commence avant, au moyen âge européen, au plan des idées, existence des premiers penseurs empiristes. Défenseur de la rationalité, contre les traditions/doctrines.

La rupture est une continuité, se réconcilier a la part chrétienne en s'enlevant des crimes chrétiens. Montrer la corruption.

Les buchets d'hérétiques

Pas des pavé, mais des images et de l'affectif, des personnages, qui font naître la réflexion. Différencier le 11ème du 14ème. 

---

Le jeu parle de la période de la moitié du 11ème, les premières institutions responsables de cette dynamique

Se finit a la peste noire en 1348, la fin du moyen âge. La contradiction finale sur une société malade.

---
Chaque niveau est associé a un lieu, une date, un évènement historique. 

- Premier niveau, cellule d'Anani, le roi de France à envoyé un de ses agents pour arrêter le Pape. 3 jours en prisons, est mort de chagrin, le roi de France a mis un pape a Avignon.
Le pouvoir royal, cet époque.

Chaque niveau étant associé a un lieu, chaque salle des catacombes permet de représenter une ville d'Europe.

Le personnage est étudiant de son propre monde
#### Villes

Rome
Clermont ferant, le concil de clermond
Lyon - La ville carrefour - Martin
Paris
Toulouse
Carcassone - La croisade de Carcassone - Le défenseur, on y rentre dans les égoûts
Lisbonne - Ygor
Inab en Syrie
Antiocq - Pour aller a Naples/Constantinoples/Puis Bologne
Avignon - Lieu caché
Inab
Marseille, les magasins, la peste
Naples (on peut revenir a Anani) - Représente la suite, le soleil après le crépuscule, après la peste, la fin du monde, les républiques Italienne portuaire.
Final, Paris, la Sorbonne

----

Le méchant final est la Paresse, au sens médiéval, l'inverse de l'Amour, le monde est bon pour toi, il te donne un corps, des relations, mais tu ne l'aimes pas en retour. 

St Thomas Daquin, penseur scolastique, pensée médiévale latine catholique principale.
Sa recherche est d'unifier théologie et philosophie naturelle.

L'un des Boss: Bernard de Clervaut (fasciste) - "l'étude la nature n'est pas différente de l'étude des textes, la rationalité est le démon"

La racine de tous, a partir de cette énergie non dépensé, elle est utilisé dans du divertissement, de la perte de temps, développement de vice. On s'enfonce dans la haine du monde. 
Des paresseux hyperactif.


Un ou plusieurs documents, qui pour chaque ville, une recherche historique, ne pas symboliser la ville par des choses anachroniques. Aucune erreur permises. Reconnaître quand même la ville, ses symboles, ses bâtiments, ses objets, faire reconnaître l'endroit au joueur sans que ce soit hurlant, pour le joueur naïf, c'est des catacombes.

Quels sont les interactions ? 
Les shops
Les portes
Les gemmes

Qu'est ce que c'est, est ce qu'on doit utiliser un modèle custom, comment ça se passe ?
Au lieu d'une porte, allier des objets entre eux. 
Un objet logique pour chaque interaction.
Conception affordante, inventivité. 

---

Look and feel, mise en scène

## Le projet

- Menu + leaderboard
- Main - Le niveau, le jeu
- Catacombs

On bosse dans les prefabs des catacombes
Une capsule, c'est la que le joueur sera
La caméra et la lumière peuvent être tweaker en live par des configs

Graphics
	Levels
	Props
	Placeholder

Convention de nommage
Organisation mettre dans placeholder catacombs

Nommage: Type_Nom_Catégorie

Camera Modes
- Catacombs
Korridor light config

Tout est a refaire au niveau des salles.

Retro render
- Post processing - recherche
- Lightning - recherche

6 to 7 light (filling point light + 6 light)

Les portes des niveaus sont des scènes, comme les catacombes (CatacombeScene_Level_Door_Nom)

### Progression

Plus on avance, plus les portes ne sont plus des portes, on peut cliquer dessus pour ouvrir la porte (Wow - instance porte)
Surprise du fait que c'est un level
A la fin, c'est un mur pété (peut-être un trou dans le sol ?)

Il y a des challenges d'observations et de déduction
2 path possibles/secondaires
Certains permettent d'accéder a des niveaux et des shops non conventionnels, 
	Carcassone to Lisbonne, un peu caché
	Antiocq to Naples
	Avignon -> Object Curse, late game
	Skip de Lisbonne a Naples -> Challenge, late game

A partir du 5ème niveau, une porte s'ouvre à Paris, toutes les portes pour y aller sont ouvertes.


## Les Shops
Trois shop a trinket
	Rome
	Lisbonne
	Naples

Shop a Marks
	Paris
	Carcassone





## Chronologie de la perfect run

#### Apogée - XII

- Bologne - évoquer le feeling chambre, enfance, revient dans le niveau final
- Cluny - **1088**
- Clermont - 
- Paris avant les catacombes - Marchant qui prend de la vie

##### Croisades

- Lisbonne - 
- Inab - **1149**
- Antioch - 
- Constantinople - 
- Bologne - 
- Rome - 
- Lyon - 

#### Catastrophe XIII

##### Perte de contrôle
- Toulouse - **1209**
- Carcassone
- Lisbonne
- Malte (ouverture vers Anagni)

#### Crise Complète XIV

- Anagni - **1303**
- Rome
- Lyon
- Avignon
- Marseille - **1348**
- Naples + Fin - Renaissance qui point

## Idée
https://www.youtube.com/watch?v=cSL2NsGpmrU
- Musique évolutive ? Zelda TOTK ?
	- Évolution verticale (dans le temps)
	- Évolution horizontale (dans l'espace)

## Ref
https://www.youtube.com/watch?v=9iTQCA7FxEQ
- Link's Awakening dungeon
- Point and clicker
	- The secret of Monkey Island
	- 

## Métadonnées & État du Projet


- **Statut** : En cours (Recherche & Proto)
    
- **Deadline Milestone** : [[2026-07-07]] (3 semaines après le stage)
    
- **Cycle de travail** : 8 semaines au total
    
    - **Semaines 1-3** : Recherche, mise en place, prototypage.
        
    - **Semaines 4-8** : Contenu, intégration, polissage.
        

---

## 🎯 Vision & Intentions

### Propos Historique

- **Réhabilitation du Moyen Âge** : Montrer le XIIe-XIIIe siècle comme le véritable berceau de la modernité (essor urbain, pensée empirique, rationalité) contre l'idée reçue d'une rupture brutale à la Révolution.
    
- **Continuité Chrétienne** : Se réconcilier avec l'héritage intellectuel (pensée latine) tout en dénonçant la corruption institutionnelle (les bûchers, le pouvoir politique).
    
- **L'Éveil par l'image** : Pas de texte massif, mais une narration par l'affect et les personnages pour différencier les époques (du XIe au XIVe).
    


---

### Antagoniste Final : La Paresse (Acedia)

- **Définition médiévale** : L'inverse de l'Amour. Le refus d'aimer le monde et le corps donnés.
    
- **Manifestation moderne** : Des "Paresseux Hyperactifs" qui s'enfoncent dans le divertissement et le vice par haine du monde.
    
- **Figure de proue** : St Thomas d'Aquin (Unification foi/raison) vs Bernard de Clairvaux (La rationalité comme démon).
    

---

## 🗺️ Structure du Monde (Les Catacombes)

_Chaque salle des catacombes représente une ville/date clé. Le joueur est un "étudiant de son propre monde"._

### Chronologie de la "Perfect Run"

1. **Apogée (XIIe)**
    
    - **Bologne** : Scriptorium, pupitres, moines copistes. Feeling "chambre/enfance".
        
    - **Cluny** (1088)
        
    - **Clermont** : Le concile.
        
    - **Paris** (Avant catacombes)
        
2. **L'Expansion (Croisades & Sud)**
    
    - **Lisbonne** (Ygor)
        
    - **Inab** (1149)
        
    - **Antioche** (Vers Naples/Constantinople)
        
    - **Constantinople**
        
3. **La Catastrophe (XIIIe - Perte de contrôle)**
    
    - **Toulouse** (1209)
        
    - **Carcassonne** : Entrée par les égouts.
        
    - **Malte** (Ouverture vers Anagni)
        
4. **La Crise (XIVe)**
    
    - **Anagni** (1303) : La cellule (Le Pape mort de chagrin).
        
    - **Avignon** : Lieu caché (La Curie).
        
    - **Marseille** (1348) : Les magasins, l'arrivée de la Peste Noire.
        
5. **Final**
    
    - **Naples** : Le soleil après le crépuscule, les républiques portuaires.
        
    - **Paris (La Sorbonne)** : Confrontation finale avec la Paresse.
        

---

## ⚙️ Systèmes de Jeu & Conception

### Interactions (Affordance & Logique)

- **Pas de "Portes" classiques** : Plus on avance, plus l'interaction devient abstraite (allier des objets, murs pétés).
    
- **Objets logiques** : Utiliser des objets d'époque comme leviers d'interaction.
    
- **Navigation** : Chemins secondaires et skips (ex: Carcassonne → Lisbonne ou Avignon pour l'objet maudit).
    

### Direction Artistique (Look & Feel)

- **Rendu** : Retro render, Post-processing spécifique.
    
- **Lumière** : Config de 6 à 7 lights (Filling + points).
    
- **Caméra** : Tweaks live via configs (Composition).
    

---

## 🛠️ Organisation Technique (Unity/Naming)

### Convention de nommage

- **Format** : `Type_Nom_Categorie`
    
- **Exemple Scène** : `CatacombeScene_Level_Door_Nom`
    
- **Dossiers** : Tout ce qui est temporaire va dans `Placeholder/Catacombs`.
    

### Hiérarchie du Projet

- `Main` (Le niveau/jeu)
    
- `Catacombs` (Prefabs des salles)
    
- `Graphics` / `Levels` / `Props`
    
- `Camera Modes` / `Light Configs`
    

---

## 📝 To-Do List

- [ ] **Utils** : ✅ (Fait) - 🚫 (Annulé) - 🟨 (En cours) - ⏳ (Bloqué)
    

### Recherche & Design

- [ ] Document de recherche historique par ville (Éviter les anachronismes).🟨
    
- [ ] Dossier Rome (Fin XIIe, 1190). 🟨
    
- [ ] Conception des interactions par "objets logiques".
    
- [ ] Recherche Post-processing & Lightning.
    

### Audio

- [ ] **Musique évolutive** (Réf: Zelda TOTK).
    
    - [ ] Évolution verticale (Temporelle).
        
    - [ ] Évolution horizontale (Spatiale).
        
- [ ] Étude de cas : _Link’s Awakening_ (Dungeons) & _Monkey Island_ (Point & Click).
    

---

## 🔗 Références & Liens

- **Musique/Ambiance** : [Vidéo Ref 1](https://www.youtube.com/watch?v=cSL2NsGpmrU)
    
- **Game Design** : [Vidéo Ref 2](https://www.youtube.com/watch?v=9iTQCA7FxEQ)
    
- **Villes clés** : [[Rome]], [[Lyon]], [[Paris]], [[Bologne]].