

#  Mumuse-joco

Ce projet, prévu pour être ultra-rapide, a pour but de faire mumuse avec le moteur Mujoco, qui se revendique comme ayant un bien meilleur moteur physique que les autres, dans le but de voir s'il comprends mieux que Pybullet la mécanique du robot Vitirover.
Le but final serait d'enfin obtenir un modèle théorique du déplacement dynamique du robot, et ainsi de pouvoir mieux le piloter.

Mujoco a des chances de réussir car il a une meilleure gestion de :

 - la physique des boucles des rétroaction (cinématique inverse) qui s'appliquent partout dans le robot (train arrière libre impose des contraintes qui se repercutent partout)

  - la physique du contact entre les roues et le sol.

En plus, il a l'air d'avoir une bien meilleure documentation que Pybullet et comme il est backé par Deep Mind, c'est clairement le bon cheval sur lequel parier.
