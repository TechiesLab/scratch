# Duel
## Progression

1. Général&nbsp;: Préparer des variables de configuration.
	- avance = l'avance des vaisseaux
	- tourne = l'angle de virage des vaisseaux
	- vitesseTir = vitesse du missile (multiple de avance)
	- attenteFinale = attente des messages de fin

1. Vaisseau1&nbsp;: déplacement

1. Missile1&nbsp;: 
	1. boucle générale&nbsp;: tir (touche pressée) ou suivre Vaisseau1; espace pour stopper.
	1. définir Tir&nbsp;: vitesse du tir et son arrêt (retour à suivre le vaisseau)
	1. définir StoppeLeTir&nbsp;: les conditions d'arrêt du tir (touché un bord, touché l'adversaire, un obstacle)

1. Dessiner les obstacles (couleur noire touchée?)

1. Régler le comportement du missile et du vaisseau (obstacles infranchissables)

1. Dupliquer vaisseau1 et missile1 vers vaisseau2 et missile2, et adapter le 2

1. Définir les comportement de fin (à partir de message&nbsp;: C'est fini, Vaisseau1 gagne, Vaisseau2 gagne)

## Touches (azerty)
```
+-------------------------+
| Vaisseau 1 | Vaisseau 2 |
+------------+------------+-----------------+
|     Z      |     Y      | Avance          |
|   Q   D    |   G   J    | Gauche / droite |
|     X      |     N      | Recule          |
|     S      |     H      | Tire            |
+------------+------------+-----------------+     
```
