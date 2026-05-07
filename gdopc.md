> *"Comment un simple flux d’air sous une voiture peut-il décider de la sécurité d’une Alpine A110 ?"*

Soit : 

> ### Pourquoi le diffuseur arrière est-il l'élément aérodynamique critique pour la sécurité de l'Alpine A110 

# L'Alpine A110

## Introduction

**Accroche**

Imaginez-vous à 250 km/h sur la ligne droite d'un circuit. À cette vitesse vertigineuse, la seule chose qui relie une voiture de sport à la route et qui maintient son pilote en vie, ce sont quatre zones de contact au sol : quatre morceaux de gomme qui ne sont pas plus grands qu'une carte postale.

**Contexte**

Pour maximiser l'adhérence de ces pneumatiques, la plupart des constructeurs de voitures de sport, comme Porsche ou Ferrari, utilisent d'imposants ailerons arrière. Ces appendices aérodynamiques sont très visibles et agressifs. Pourtant, si vous regardez l'Alpine A110 moderne, l'une des sportives françaises les plus reconnues, vous remarquerez une ligne d'une pureté absolue, sans aucun aileron. Elle conserve la silhouette fluide de son ancêtre championne des rallyes dans les années 70.

**Problématique**

Dès lors, une question se pose : comment, sans cet artifice mécanique visible, l'Alpine A110 parvient-elle à rester plaquée au sol à plus de 250 km/h ? Autrement dit : comment un simple flux d'air passant sous une voiture peut-il décider de la sécurité de ses passagers ?

**Plan**

Pour y répondre, nous utiliserons les outils de la physique. Nous analyserons d'abord les risques mécaniques liés à la haute vitesse en dressant le bilan des forces. Ensuite, nous plongerons au cœur de la mécanique des fluides pour comprendre comment le fond plat de l'Alpine exploite le théorème de Bernoulli. Enfin, nous verrons pourquoi cette solution est physiquement beaucoup plus efficiente qu'un aileron classique.

## I. La portance, un danger pour la grande vitesse

Pour comprendre le danger, modélisons notre voiture en mouvement. Le système étudié est la voiture de centre de masse G, dans le référentiel terrestre supposé galiléen.
À faible vitesse, le bilan des forces est simple : selon la seconde loi de Newton, la voiture est soumise à son poids, dirigé vers le bas, et à la réaction normale de la route, dirigée vers le haut. La force de frottement des pneus sur la route — l'adhérence — est directement proportionnelle à cette réaction normale. Plus la voiture appuie sur le sol, plus elle a d'adhérence.
Mais à haute vitesse, l'air modifie la donne. La carrosserie d'une voiture se rapproche physiquement du profil d'une aile d'avion. L'air percutant l'avant se sépare en deux : le flux supérieur, contraint par le toit bombé, doit parcourir une plus grande distance et accélère donc par rapport au flux inférieur. Cette différence génère deux forces aérodynamiques :
 1. **La traînée** (horizontale), qui freine la voiture.
 2. **La portance** (verticale vers le haut), ou *lift*.
À 200 km/h, cette portance peut littéralement soulever le véhicule, comme lors de l'accident au Nürburgring en 2015. La réaction normale diminue, le train arrière s'allège et l'adhérence disparaît, rendant tout virage ou freinage catastrophique. Pour l'A110, les ingénieurs devaient annuler cette force sans ajouter d'aileron.

## II. La voiture dompte son air, grâce à l'effet Venturi et Bernoulli

Sous l'Alpine, le châssis est caréné par une plaque totalement lisse : le **fond plat**. À l'arrière, ce fond remonte pour former un canal évasé appelé **diffuseur**.
En modélisant l'air comme un fluide incompressible et l'écoulement comme stationnaire, nous appliquons le théorème de Bernoulli le long d'une ligne de courant :

$$P + \frac{1}{2}\rho v^2 + \rho g z = \text{constante}$$


Puisque l'air circule horizontalement, les variations d'altitude (z) sont négligeables. Le théorème se simplifie ainsi :

$$P + \frac{1}{2}\rho v^2 = \text{constante}$$


Cela signifie que si la vitesse (v) augmente, la pression (P) diminue.
Le débit volumique $D\_v$ devant se conserver ($D\_v = S \times v$), l'air est obligé d'accélérer violemment dans l'espace minuscule entre le sol et le fond plat (où la surface S est très réduite). C'est l'**effet Venturi**.
Cette accélération fait chuter la pression sous la voiture. La différence avec la pression atmosphérique supérieure crée une force pressante ($F = P \times S$) dirigée vers le bas. La voiture est littéralement aspirée par la route. Le diffuseur, en s'évasant, permet à l'air de décélérer doucement pour retrouver la pression ambiante, agissant comme une pompe qui optimise cette dépression.

## III. Diffuseur contre Aileron : L'efficience physique de l'Alpine

Un aileron classique est une aile inversée efficace mais coûteuse en énergie à cause de la **traînée induite**. Il agit comme un parachute, dégradant le coefficient de pénétration dans l'air ($C\_x$) selon la loi de la traînée :

$$F_x = \frac{1}{2} \rho v^2 C_x S$$



L'intelligence de l'A110 réside dans son efficience. Le couple fond plat/diffuseur génère une "déportance gratuite" avec une traînée presque nulle. Cela permet à l'Alpine d'atteindre des performances égales à des concurrentes plus puissantes tout en restant légère (1100 kg), créant un cercle vertueux : moins de poids fatigue moins les pneus et augmente l'agilité.

## Conclusion

**Bilan**

La sécurité à haute vitesse est menacée par la portance. L'Alpine A110 résout ce problème par une application magistrale du théorème de Bernoulli : son fond plat transforme l'air en une ventouse invisible. C’est un triomphe de la finesse sur la force brute.

**Ouverture**

Cette maîtrise de l'écoulement inférieur est aujourd'hui cruciale pour les véhicules électriques. Le carénage du soubassement n'y assure plus seulement la stabilité, mais devient le facteur clé de l'autonomie en réduisant la résistance à l'air.
Je vous remercie pour votre attention.
