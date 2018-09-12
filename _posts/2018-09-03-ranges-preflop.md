---
layout: post
image: /img/theory.png
title: La théorie du jeu optimal

---

Online, avec le rake, le poker n'est pas un jeu a somme nul mais a somme négative, il faut donc avoir un edge pour ne pas perdre d'argent (voila pourquoi il faut jouer et cibler des joueurs moins bons que nous). Lorsqu'on décide de jouer une stratégie exploitable, nos adversaires peuvent très vite s’en rendre compte, et en profiter pour nous exploiter. Nous allons donc chercher l'inexploitabilité. Pour cela il faut se pencher sur la théorie des jeux. La théorie des jeux est un ensemble d'outils qui permet de définir une action optimale à un moment donné. Grace à ses outils, nous allons batir une stratégie inexploitable, qui consiste à jouer à l'équilibre dans toutes les situations, avec le bon ratio de value bets et de bluffs. Si deux joueurs jouent l'un contre l'autre optimalement, ils atteignent ce que l’on appelle un "équilibre de Nash," où aucun des deux n'a intérêt à dévier de cette stratégie optimale. L'idée est donc d'avoir une bonne compréhension de cette stratégie, d’appréhender les situations d’équilibre de chaque spot et d'en appliquer une approximation, pas besoin d’être parfait !.
{: .text-justify}

Cette stratégie est une base pour construire un jeu solide. Pour exploiter nos adversaire on va chercher en quoi le joueur dévie du jeu inexploitable. En connaissant cette stratégie on va savoir quand il est pertinent de dévier de l'équilibre (fréquence dans chaque spots - il bluff moins - il value trop thin).
{: .text-justify}
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTYxMjExOTU3MCw3MzA5OTgxMTZdfQ==
-->