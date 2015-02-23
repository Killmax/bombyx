Projet réalisé en Python2

Sujet :

"Dans les années 70, la théorie du chaos a permis de mieux comprendre l’évolution de
certaines espèces animales.
Prenons l’exemple des papillons.
Disons, des bombyx.
Plus le nombre de papillons d’une génération est important, plus la génération suivante
sera peuplée, mais moins il y aura de ressources disponibles, et donc moins la génération
suivante va se développer.
L’évolution du nombre de bombyx d’une génération sur l’autre n’est donc pas triviale ;
en appelant x i le nombre de papillons à la i ème génération, le nombre de papillons est
modélisé ainsi :

x1 = 10
x(i + 1) = k * x(i) * ((1000 - x(i))/1000) pour i >= 1

k est appelé le taux de croissance, et varie de 1 à 4.
Afin de pouvoir étudier cette évolution, on vous demande de tracer la courbe du nombre
d’individus en fonction de la génération.
Pour cette option, votre logiciel prendra comme unique paramètre k, et tracera la
courbe représentant l’évolution des 100 premières générations de papillons.
De plus, il vous est demandé de tracer un schéma synthétique récapitulant les résultats
obtenus : pour cette option, votre logiciel prendra comme entrée i min et i max , et tracera
les valeurs de x i (pour toutes les valeurs de i de i min à i max ) en fonction de k (k variant
de 1 à 4 par pas de 0.01)."