# PROOF OF CONCEPT: Improved Perlin Noise

Petit exécutable tout mignon sous licence GNU/GPLv3, qui implémente le Bruit de Perlin amélioré
et génère une heightmap stocké dans un fichier png.
Assurez vous d'avoir libpng installé sur votre system sinon ça va pas l'faire.

## Pour Compiler

	make

## Pour nettoyer (supprimer le binaire et les éventuelles fichiers .o)

	make clean

## Comment ça marche?

Une fois compilé, dans un terminal, tapez

	./improvedPerlinNoise <Puissance de deux>

par exemple

	./improvedPerlinNoise 256

ou bien encore

	./improvedPerlinNoise 512

ou même encore, si vous avez du temps à perdre

	./inmprovedPerlinNoise 4096

À l'issue de cette commande un fichier png nommé 'terrain.png' apparait.

C'est votre heightmap :)
