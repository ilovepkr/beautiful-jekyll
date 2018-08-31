---
layout: post
title: Les fondamentaux
image: /img/technique.png
---

## Les bases mathématiques

La cote du pot ou la formule du risk / reward
C'est le ratio entre la taille du pot et le coût d'un potentiel CALL.
Si à la River un jouer BET 30€ dans un pot de 50€, le joueur qui va CALL risquera 30€ pour gagner 80€ et il aura donc une cote de 8:3. Il devra alors gagner au moins 27,3% du temps  pour que son CALL soit profitable.

$C_{pot} = \dfrac{Risque}{Risque + Récompense} = \dfrac{Call}{Call + Pot}$

Quand le joueur est en bluff, il mise pour essayer de prendre le pot, donc si a la River, le joueur mise 30€ pour prendre un pot de 50€, il aura une cote de 5:3, et pour être profitable son bluff doit passer 37,5% du temps.

$E = \dfrac{Risque}{Risque + Récompense} = \dfrac{Bet}{Bet + Pot}$


&nbsp;
## L'équité

L'équité représente la chance de gagner d'une main face à la main ou la range d'un adversaire. Par contre, ce n'est pas parce qu’une main à plus d'équité qu'une autre, que c'est une meilleure main et qu'elle est plus profitable à jouer.

Prenons l'exemple d'un call préflop.

Une main comme A9 n'est pas un bon call car elle a beaucoup d'équité contre la range de check/fold de notre adversaire. De plus Ahi sans kicker est souvent trop faible pour être checker sur 3 streets et essayer de gagner au showdown. Enfin quand on misera cette main, elle ne réalisera jamais son equité car toutes les plus mauvaises mains de notre adversaire devront fold puisque A9 ne bat presque jamais une main de la range de value de notre adversaire au flop et qu'il ne check/callera jamais plusieurs street avec moins bien.

Une main comme 98s ne flopera pas souvent une main qui battera les mains fortes adverses, cependant elle flopera souvent un draw ou une paire avec 5 outs et pourra potentiellement se transformer en main forte.
On pourra aussi utiliser son équité efficacement en semi bluffant la turn ou la river.

Prenons un autre exemple.

Nous callons en position et le flop vient : K73r
66 et 98s ont la même équité ici cependant float le flop avec 98s est un meilleur move ici que de call avec 66.
98s a 22 cartes pour s'améliorer à la turn et permettre de call aussi turn ce que ne possède pas 66.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwMTUxMTkxNTgsMTE0ODc0Nzc3NF19
-->