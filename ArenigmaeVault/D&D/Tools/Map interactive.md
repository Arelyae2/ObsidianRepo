
Ce pose aussi la question des visuels, trouver les tilemap s'avère compliqué, surtout avec une DA de DND précise.

Inkarnate semble être une bonne piste, a 5 euro par moi c'est ok, les tilempa serait ensuite exporté vers Unity en image (la grid serait préfaite de Inkarnate)

Pour l'outil de **Map interactive**, on y mettrait:

taille des maps: 8192 x 6850
## Le système

- Une navigation d'un environnement de base en top down (Zoom, drag...)

- Un fog of war qui serait plus ou moins sévère dans les espaces éclairés/la nuit plus sombre. Beaucoup plus permissif dans les villages et lieux publics qui ne nécessitent pas d'explorations

- Un système a double fenêtre avec une mini map (schématiser la fenêtre admin) pour faire spawn des enemis et bouger les joueurs.

- Système multijoueur local ou on lance deux instances et les deux communiquent entre elles.

- Les fenêtres ne doivent pas disparaître lorsqu'on en change ni se déconnecter du son ou se "mettre en pause"

## Les Ennemis

- Fenêtre style bg3 pour aisément voir leur stats, faiblesses et résistance.
  
- Création de profile, classé selon plusieurs facteurs (CHallenge Rate, type, environment...)

![[Pasted image 20260105183912.png]]

- Pouvoir les faire spawn/diparaître sur la carte comme des prefab, traquer leur vie, et leur potentiel loot peut-être.

- 