# Aperçu des programmes
## Programmes simples ou progressifs

- _Robert_, allo&nbsp;: Comprendre les messages synchrones et asynchrones avec Tintinabulus et Galadrielle.

- _Robert_, duel&nbsp;: voyez  [DUEL\_README.md](https://github.com/TechiesLab/scratch/blob/master/programmes/duel/DUEL_README.md).

- _Robert_, frog&nbsp;: jeu de type "frog" avec une grenouille qui doit traverser la route sans se faire écraser. Pour les détails, voyez [FROG_GAME.md](https://github.com/TechiesLab/scratch/blob/master/programmes/frog/FROG_GAME.md)
	1. frog 0.sb2&nbsp;: orientation et déplacement de Frog, la grenouille
	1. frog 1.sb2&nbsp;: introduction de Fox qui parcourt la route. Réglage de la vitesse de Fox. Si Frog touche Fox, le jeu s'arrête.
	1. frog 2.sb2&nbsp;: idem frog 1, mais on ajoute Bat1 et Cat1 flying qui parcourent la route
	1. frog 3.sb2&nbsp;: on enjolive les collisions entre Frog et le reste
	1. frog game.sb2&nbsp;: jeu complet; ajout des points; 1 point à chaque fois que Frog traverse la route en étant sauf (notion de bascule introduite)
	1. Exemple&nbsp;:  [frog game](https://scratch.mit.edu/projects/211884283/) sur scratch.mit.edu

- _Robert_, je\_fais\_mon\_cinema&nbsp;: décomposer un gif animé en "frames" et faire une séance de cinéma à l'aide des costumes. Pour décomposer un gif animés en ses images (frames) voyez ce site: [https://www.bloggif.com/gif-extract](https://www.bloggif.com/gif-extract)
[Exemple amélioré](https://scratch.mit.edu/projects/217679845/)

- _Robert_, le\_pied\_a\_l\_etrier&nbsp;: 6 petits programmes basiques utiles à la découverte de scratch.

- _Robert_, programmer\_un\_saut&nbsp;: apprentissage progressif f'un saut type "plateforme". Un lutin saute de plateformes noires en plateforme noires, meurt sur la couleur bleue, et change de décor ou gagne sur une autre couleur.
	1. Programmer un saut0.sb2&nbsp;: Saut linéaire, le lutin (dragon) monte tant qu'on appuie sur la flèche haut, sinon il descend + déplacements latéraux. Problème du dragon (qui reste scotché au noir dès qu'il le touche de n'importe quelle partie).
	1. Programmer un saut1a.sb2&nbsp;: Saut linéaire, le dragon monte tant qu'on appuie sur la flèche haut, sinon il descend + déplacements latéraux. Le problème du dragon résolu (il est maintenant scotché à une base qui est le lutin manipulé par les touches, le dragon la suit).
	1. Programmer un saut1b.sb2&nbsp;: Saut avec différentiel d'accéleration ver sle haut, le dragon monte de + en + lentement tant qu'on appuie sur la flèche haut et finit par s'arrêter, puis / sinon descend + déplacements latéraux. Le problème du dragon n'est pas résolu.
	1. Programmer un saut2.sb2&nbsp;: = 1a + 1b
	1. [Exemple](https://scratch.mit.edu/projects/214474955/)  d'un jeu plus complet avec 3 niveaux et plateformes mobiles. 

- _Robert_, race&nbsp;: petit jeu de course entre 2 lutins.
	- Race1.sb2&nbsp;: Déplacement avec appui continu (et concurrent) sur les touches "m" et "q"
	- Race1.sb2&nbsp;: Déplacement avec appui successif sur les touches "m" et "q". Introduction de la notion de drapeau.
