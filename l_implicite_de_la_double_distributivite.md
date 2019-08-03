L'implicite de la double distributivité
=======================================

J'ai souvent remarqué que certaines personnes ont du mal à progresser en
mathématiques en partie parce qu'elles ne pensent pas aux notions de la
bonne manière. Ce qui, au fond, n'est guère étonnant, puisque, en y
regardant de plus près, on constate que cette bonne manière d'y penser n'est
pas enseignée, au moins en général dans le système français. Je vais essayer
de commencer à y remédier sur un exemple.

Je vais donc m'adresser à un hypothétique élève arrivant en début de
première générale spécialité mathématiques (ce qu'on appelait il y a peu
première S, ou à la rigueur ES) qui souhaite la réussir avec brio. Je
parlerai de l'intuition qu'il faut avoir pour manipuler les objets
efficacement, et je m'appuierai sur l'exemple de la double distributivité,
parce que c'est à la fois une technique très utile et un problème qui permet
d'introduire de nombreuses notions, et parce que c'est hélas quelque chose
qui manque à de nombreux élèves au niveau première.

Je m'adresserai à cet élève hypothétique en la ou le tutoyant. Et
j'utiliserai le pronom « vous » pour m'adresser à toi et tous tes camarades
dans la même situation. Cependant, je pense que ce que je vais dire peut
intéresser ceux qui ont à expliquer ces notions aux élèves, ainsi que ceux
qui s'intéressent aux mathématiques en général et peuvent ne pas avoir pensé
en ces termes à certaines choses que je vais dire.

Je dis « la » bonne manière, mais c'est un abus de langage : il est presque
certain qu'il y ait d'autres bonnes manières d'y penser, peut-être même de
meilleures que ce que je vais évoquer. Mais ce dont je suis à peu près sûr,
c'est que ce que je vais raconter est plutôt meilleur que ce qui se fait
actuellement souvent dans l'enseignement français.

Ce qui manque dans les explications, ce sont des éléments qui permettent de
mieux bâtir une intuition et de relier les notions entre elles. Les
personnes déjà l'aise avec le calcul ont certainement développé cette
intuition par elles-mêmes, mais elles ne l'ont souvent pas formalisée. Ces
idées restent implicites, et donc ne sont pas traduites dans l'enseignement,
les élèves devant alors les redécouvrir par eux-mêmes. Je vais essayer
d'expliciter cet implicite.

Avant de commencer, je tiens à rendre hommage à Grant Sanderson et sa
[chaîne YouTube 3Blue1Brown][3b1b], où il publie des vidéos de vulgarisation
des mathématiques en insistant énormément sur l'intuition, avec une démarche
qui me semble aller vraiment dans la bonne direction. Son style a été une
inspiration précieuse pour cet article.

Ce texte est long. Bien trop long pour être la base d'un cours, même réparti
sur toutes les années où ce serait pertinent. Il est long parce que je suis
bavard et que j'aime bien faire des digressions, et aussi parce que je veux
mettre tous les éléments auxquels je pense qui peuvent être utiles. Je dois
également passer un certain temps à déconstruire certaines formes
d'intuition que je pense stériles, et à reconstruire en repartant de très
tôt. Je pense cependant que les éléments que je développe peuvent être
utilisés pour faire évoluer la manière de présenter certaines notions de
manière à les rendre plus digestes, sans avoir à gonfler l'horaire
d'enseignement.

En lisant, tu te diras souvent « mais je le sais déjà, ça », et aussi
« c'est évident ». C'est difficilement évitable, je ne te connais pas
personnellement. Ce que j'espère, c'est que certains passages, même de
petits détails, te feront noter « tiens, je n'y avais jamais pensé de cette
manière ». Chaque nouvelle manière de penser à une notion est une chance
d'avoir le déclic qui éclaire tout le voisinage.

Je parlerai aussi, aux quelques moments où c'est pertinent, de la manière
d'apprendre : comment consolider la compréhension nouvellement acquise pour
en faire une compétence en laquelle tu peux avoir confiance.

Il y a fort à parier que certaines parties t'échappent en première lecture.
C'est normal, mon texte est touffu. Mais si tu as plus tard les déclics que
j'espère, tu verras peut-être qu'en seconde lecture tout devient plus clair,
provoquant de nouveaux déclics.

Bon courage !

(Désolé, la présentation des formules est moche parce que ce document est
rédigé initialement en Markdown pour produire du HTML et du PDF.)

## L'énoncé du problème

On pose la question :

> Développer (2x+3)(5−4x), où x est un nombre réel quelconque.

La réponse attendue est:

> (2x+3)(5−4x) = −8x²−2x+15

Pour espérer suivre le cours de mathématiques niveau première puis terminale
confortablement, je pense que tu as besoin d'être capable de faire ce calcul
directement, sans presque jamais te tromper et rapidement. Mais pas comme un
singe savant qui a appris un truc, comme un mathématicien qui comprend
parfaitement ce qu'il fait et a assez d'entraînement pour le faire sans
hésiter.

## Comment travailler les maths

Quand tu apprends une nouvelle méthode, tu vas probablement prendre un
exercice et le résoudre en suivant la démarche du cours, avec de nombreuses
hésitations au long du chemin. Et arrivé au résultat juste, tu te dis
« c'est bon » et tu passes à la suite. Non ? Ce n'est hélas pas suffisant.

Pour faire comprendre les choses, j'aime bien faire l'analogie avec un
sport, car de ce point de vue, le cerveau marche pas mal comme un muscle. Et
pour commencer, je rappelle qu'on ne progresse pas en course en regardant le
prof d'EPS courir autour du terrain. Il faut courir soi-même, c'est l'effort
répété qui renforce le muscle.

De plus, si on pense à un sport assez technique, qui demande d'apprendre des
gestes précis, l'entraîneur insiste probablement souvent : n'essaie pas
d'aller vite tout de suite, force-toi à faire le mouvement correctement,
recommence pour corriger tes erreurs mêmes minimes. Et une fois que les
muscles et les nerfs seront habitués aux sensations du mouvement, les
hésitations disparaîtront et la vitesse viendra naturellement.

C'est aussi comme ça qu'on apprend à écrire : il faut faire des lignes et
des lignes de lettres, soigneusement formées.

Et c'est comme ça qu'il faut aborder les maths, et en particulier le
calcul : commencer par les exercices types de base, les faire soigneusement,
recommencer jusqu'à ce que les erreurs soient assez rares, et encore jusqu'à
ce que la vitesse vienne.

Pour ça, il faut une quantité illimitée d'exercices disponibles et un
correcteur dévoué. Heureusement, pour le genre d'exercices dont il est
question ici, il est assez facile de simplement inventer les données, et on
peut vérifier le résultat final par exemple en utilisant une calculatrice
graphique. On peut également avoir recours à l'excellent site web
[wa][WolframAlpha]. À défaut, on peut travailler en groupe et pratiquer la
correction mutuelle, et en dernier recours demander au professeur.

## Qui a décidé les règles de calcul ?

J'en viens aux mathématiques proprement dites, et je vais commencer par
quelques questions philosophiques de base.

Depuis des années, on vous apprend des règles de calcul. Si vous les suivez,
c'est juste, vous avez 20, si vous ne les suivez pas, ou pas correctement,
c'est faux, vous avez 0. Mais qui a choisi les règles, et pourquoi ?

Ma réponse courte est que les règles se sont imposées d'elles-mêmes, mais
c'est un peu plus subtil que ça.

On peut voir les mathématiques comme une gigantesque partie de Badaboum, où
il faut empiler des pièces de formes variées et où celui qui provoque
l'effondrement a perdu. Mais c'est une partie en collaboration : nous
cherchons ensemble à bâtir un édifice aussi beau et grandiose que possible,
et si ça s'effondre, nous avons tous perdu.

On peut constater la solidité de l'édifice quand il s'accorde avec la
réalité. Par exemple, les sciences physiques nous donnent des formules pour
calculer le comportement d'objets concrets. Si le résultat fourni par le
calcul est conforme au résultat observé par l'expérience, ça confirme non
seulement la formule donnée par le physicien, mais également la rigueur du
calcul mené par le mathématicien.

Si ça ne colle pas, en revanche, il faut savoir quel bout est à blâmer : la
physique ou bien les mathématiques ? C'est pourquoi pour savoir si les
mathématiques risquent de s'effondrer, on cherche plutôt des indices
intérieurs : si les calculs ne collent même pas entre eux, si on arrive à
des résultats différents en faisant le même calcul de plusieurs manières,
etc.

En résumé, si on arrive à démontrer quelque chose de manifestement ridicule,
absurde, comme 0=1, on a perdu.

Quant à savoir ce qui décide si le raisonnement tient, ce qui marche et qui
ne marche pas… Qu'est-ce qui décide qu'une pièce plate tient en équilibre
tandis qu'une pièce pointue tombe ? Ce sont des questions philosophiques
auxquelles je n'ai pas de réponse satisfaisante. Heureusement, la philo
c'est l'an prochain, et on ne posera pas de questions aussi difficiles.

Mais je n'ai pas fini de répondre à la question. Je reprends mon analogie
sportive, ou ludique d'ailleurs : il ne suffit pas de connaître les règles
du jeu pour être bon, il faut aussi maîtriser les techniques qui marchent et
éviter celles qui ne marchent pas. Dans certains sports, quelques
centimètres de différence dans le placement de la main ou de la jambe
peuvent faire la différence entre la victoire ou la défaite. Inculquer la
bonne position de la main, de la jambe, fait aussi partie du rôle de
l'entraîneur.

Les bonnes techniques ne sont pas écrites dans les règles, mais elles sont
induites par les règles. Personne ne les a décidées, on les a seulement
constatées : tel athlète faisait tel mouvement et gagnait souvent, donc on
l'a imité. Au fil du temps, les entraîneurs ont accumulé une somme de
connaissances des meilleures techniques et les enseignent à leurs élèves.

On voit souvent dans la fiction le cliché des écoles d'arts martiaux où sont
transmises des techniques ancestrales extrêmement pointues et puissantes. En
mathématiques, ça fait plus de vingt-cinq siècles que nous peaufinons nos
techniques. Donc elles sont assez raffinées et efficaces, et il y a beaucoup
à apprendre. (Et puis, c'est un secret, les titulaires de la médaille Fields
sont capables d'envoyer des boules d'énergie avec leurs petits doigts.)

Enfin, le cadre scolaire exige que nous utilisions tous à peu près les mêmes
techniques. Donc même si parfois il y aurait plusieurs méthodes, plusieurs
manières de poser les problèmes et de les résoudre, aussi efficaces les unes
que les autres, l'institution va insister pour qu'on en choisisse une en
particulier.

## Lire une formule

Venons-en à la pratique. Mais il va falloir remonter loin. Prenons une
formule simple :

```
2+2×2=6
```

Une formule n'est pas juste une suite de symboles mathématiques, de même
qu'une phrase n'est pas juste une suite de mots. Les mots doivent respecter
une structure, la grammaire, pour former une phrase compréhensible. Au
collège, vous avez appris à analyser cette structure, à trouver le verbe, le
sujet, les compléments et voir comment ils s'organisent. La structure peut
être assez compliquée : il peut y avoir des propositions subordonnées dans
des propositions subordonnées qui elles-mêmes contiennent des groupes
nominaux formés de noms et d'adjectifs, etc.

Analyser une phrase, c'est trouver les relations logiques entre les mots. On
peut par exemple les représenter entourant les groupes avec des patatoïdes
(une courbe fermée vaguement régulière, comme une pomme de terre ; j'aime
bien ce mot). On peut aussi y penser comme à un arbre généalogique : un
parent avec deux branches pour deux enfants ressemble à un verbe avec une
branche pour le sujet et une branche pour le complément.

Cette structure d'arbre logique (pas généa-) est très importante, et elle se
retrouve telle quelle dans les formules mathématiques. De plus, les formules
ont besoin d'être extrêmement précises, de ne pas laisser de place à
l'ambiguïté, donc quand on a l'habitude, construire l'arbre à partir de la
formule ne demande pas de réflexion.

Soit dit en passant, quand on programme un ordinateur (ou une calculatrice,
qui n'est qu'un ordinateur limité) pour manipuler une formule, c'est la
structure de l'arbre qui est utilisée dans sa mémoire, pas le texte de la
formule.

Donc, revenons à notre 2+2×2=6, et cherchons à l'analyser. Pour la première
étape, c'est facile parce que l'analogie avec le français marche très bien :
il y a un verbe dans la formule. Ce verbe, c'est le symbole =, et il est
presque synonyme du verbe *être* : 2+2×2 *est égal* à 6. Il y a d'autres
verbes : <, ∈, ⟺, etc., mais = est de loin le plus important.

Il n'y a rien à analyser dans 6. En revanche, dans 2+2×2, il faut
décomposer. Le bout suivant à regarder, c'est le +, qui correspond un peu à
la conjonction de coordination *et* : on ajoute 2 *et* 2×2. Et pour finir,
le × est une opération au même titre que + et marche pareil pour la
grammaire.

## Les priorités

Attention cependant, je suis passé trop vite sur une grosse subtilité. Si on
reprend la formule :

```
2+2×2
```

Il y a deux manières de la comprendre :

```
2  +  2×2
2+2  ×  2
```
Et de même

```
2×2+2
```

pourrait se comprendre :

```
2  ×  2+2
2×2  +  2
```

On peut avoir le même phénomène en français, par exemple sur la carte d'un
restaurant qui vous proposerait « fromage ou dessert et café » : si vous
prenez le fromage, avez-vous droit au café ? L'ambiguïté est alors levée par
la présentation de la carte, ou alors par la ponctuation : « fromage ou
dessert ; et café », et en dernier recours par le bon sens et les habitudes.

En mathématiques, on ne peut pas compter sur le bon sens ou les habitudes
pour distinguer deux formules similaires, il faut donc établir des règles de
présentation, de ponctuation et de lecture précises.

La règle que vous avez apprise, c'est que la multiplication a priorité sur
l'addition, qu'il faut donc faire la multiplication en premier. Ça répond à
la question posée : les bonnes lectures sont respectivement :

```
2  +  2×2
2×2  +  2
```

On peut dire que le × colle plus fort les nombres ensemble que le +.

Et c'est là que je vois un grave problème dans l'explication. Parce que
quand on dit que quelque chose a priorité, on a tendance à penser qu'elle
est plus importante. Or ici, c'est plutôt le contraire, c'est le + qui est
le plus important dans cette formule.

D'ailleurs, il est vrai que pour *calculer* la valeur de cette formule il
faut s'occuper du × en premier, mais pour *analyser* la formule, c'est le +
qu'il faut regarder en premier, et c'est vrai également pour de nombreuses
tâches, comme la dérivation, que tu apprendras bientôt.

Jusqu'à il y a quelques années, avant que tout le monde ait un smartphone
surpuissant, les gens normaux (c'est à dire pas les collégiens et lycéens)
utilisaient des calculatrices qu'on appelle « quatre opérations » (même si
en pratique elles en ont un peu plus). Par rapport aux calculatrices
scientifiques, elles n'ont presque aucune mémoire, donc elles font les
calculs immédiatement.

En conséquence si on tape « 2+2×2= », dès qu'on appuie sur ×, elles
calculent le résultat de 2+2, font la multiplication avec ce 4 et répondent
finalement 8. Il n'est pas possible de leur faire respecter les priorités
(mais elles ont une touche supplémentaires pour faire des sommes de
résultats).

Pour les ingénieurs, il existait une autre gamme de calculatrices, celles
qui travaillent en *notation polonaise inversée*, RPN pour les anglophones
paresseux. Dans ce système, on donne plusieurs nombres successivement à la
calculatrice, et quand on appuie sur une touche d'opération, elle calcule
avec les deux derniers nombres et met le résultat à la place. Donc pour
calculer 2+2×2, on tape d'abord « 2 2 2 », puis ×, qui prend les deux
derniers 2 et les remplace par 4, et enfin +, qui prend le premier 2 et ce 4
pour répondre 6. Pour donner priorité à l'addition, on tape à la place
« 2 2 + 2 × », je laisse en exercice le soin de le vérifier.

Pour ceux qui y sont habitués, la notation polonaise inversée est très
pratique, car elle permet de faire n'importe quel calcul avec un minimum de
touches. Et au fond, c'est dans cet ordre que *doit* se dérouler le calcul,
on ne peut pas faire autrement que de calculer les résultats intermédiaires
avant le résultat global. Mais c'est avoir la tête dans le guidon, c'est se
focaliser sur la technique de calcul plutôt que sa logique.

Quand ton professeur te disait que pour calculer 2+2×2 il faut calculer 2×2
en premier, il pensait déjà à l'exercice qu'il allait te donner au contrôle,
« calculer 5+3×7 », et il te donnait la recette pour le résoudre. Mais il ne
pensait pas que bientôt, dès qu'il y aurait des lettres dans le calcul, il
ne suffirait plus de calculer, il faudrait absolument comprendre la
structure de la formule.

Je pense qu'il serait plus efficace d'enseigner dans l'autre sens : dire que
le + est l'*opération principale* de la formule. Le résultat de la formule
est le résultat de l'opération principale, et pour le calculer il faut
commencer par calculer les nombres qu'on doit additionner, ce n'est plus
qu'une question de bon sens, comme se rendre compte qu'il faut enlever ses
chaussures avant ses chaussettes.

Pour le dire de manière provocante : on enseigne aux élèves à lire les
formules en notation polonaise inversée, il serait temps qu'on arrête.

## Les parenthèses

Je viens d'expliquer en détail que « 2+2×2 » doit se comprendre comme
« 2  +  2×2 » plutôt que comme « 2+2  ×  2 ». Ça amène naturellement la
question : comment est-on censé exprimer le second ?

On ne peut pas compter sur l'espacement comme je l'ai fait, ce n'est pas
robuste : as-tu laissé cet espace plein de blanc correcteur pour séparer les
bouts de la formule ou bien pour ne pas attendre que le blanc sèche ?

Si on écrit avec un stylo plutôt qu'un clavier comme moi maintenant, on peut
entourer le 2+2. C'est facile, c'est clair, ça marche parfaitement.

Si on doit exprimer un calcul plus compliqué, on peut avoir besoin
d'entourer plusieurs morceaux de formule. Dans ce cas, il est très important
d'observer ce fait : *les patatoïdes qui entourent les morceaux de formule
ne peuvent pas se croiser.* Soit ils sont complètement séparés, soit l'un
est complètement à l'intérieur de l'autre.

Entourer les bouts de formule marche bien, mais c'est un peu fastidieux, il
faut être très soigneux pour que ça ne devienne pas illisible, et avec un
clavier ce n'est vraiment pas pratique. Heureusement, les formules
s'étendent horizontalement mais pas verticalement, donc il suffit de
dessiner les parties extrêmes des patatoïdes, et ça devient donc des
parenthèses : quand on écrit « (2+2) », c'est une manière commode d'écrire
« 2+2 » entouré.

Quand il y a plusieurs groupes entourés, il faut faire attention de bien
montrer quelles parenthèses vont ensemble. Pour ça, on conseille souvent de
changer leur forme, représenter certaines par des crochets. On peut aussi
jouer sur la taille, de grandes parenthèses pour entourer un gros groupe,
des petites pour entourer un petit groupe.

La condition que les groupes ne se croisent pas se traduit par le fait que
les parenthèses doivent être équilibrées : « …[…(…)…]… » est correct,
« …[…(…]…)… » ne l'est pas. C'est toujours la dernière parenthèse qu'on a
ouverte qu'il faut fermer en premier. Comme des objets empilés les uns sur
les autres : on ne peut reprendre le premier qu'on a posé et qui est tout en
bas de la pile qu'après avoir repris tous les autres.

## L'associativité

J'ai expliqué comment comprendre « 2+2×2 », qui est pareil que « 2+(2×2) »,
et « (2+2)×2 ». Mais que faire quand on a plusieurs fois la même opération ?
Comment lire « 2+3+4 » ?

Celui-là, il est facile, parce que si on le comprend comme (2+3)+4, on
trouve 5+4=9, et si on le comprend comme 2+(3+4), on trouve 2+7=9 aussi.

Quand on n'a que des additions, on va trouver le même résultat quel que soit
l'ordre dans lequel on calcule et additionne les termes. Les mathématiciens
disent que l'addition est *commutative* et *associative*. Techniquement, on
considère que c'est la première décomposition qui est la bonne, mais du
point de vue de l'intuition, il vaut mieux y penser comme une seule addition
avec de nombreux termes.

C'est pareil pour la multiplication : 2×3×4=24 quel que soit l'ordre dans
lequel on multiplie les nombres. La multiplication est également commutative
et associative, et on peut y penser comme une seule multiplication de trois
nombres.

## Et les soustractions dans tout ça ?

Il reste à parler des soustractions. Et des nombres négatifs, parce que ça
va ensemble. Un nombre négatif, c'est un nombre qui fonctionne à l'envers.
Faire « moins trois » pas vers l'avant, c'est faire trois pas en arrière.

Mettre un moins devant quelque chose, c'est retourner son effet.

Si on retient ça, on a gratuitement la règle des signes, puisque quand on
retourne deux fois de suite, on revient au point de départ.

Une soustraction, c'est une addition dont un des termes, celui de droite,
fonctionne à l'envers : on part du cinquième étage, si on monte de trois
étages, on arrive au 5+3=8, mais si on descend de trois étages, on arrive au
5−3=2. C'est pareil que de dire qu'on est monté de « moins trois » étages :
5−3 veut dire la même chose que 5+(−3).

Et si on fait le contraire : on part du 3 et on descend de 5 ? Cette
fois-ci, c'est le 5 qui est à l'envers et le 3 qui est à l'endroit, donc
tout est retourné par rapport à la situation précédente, donc le résultat
lui-même est retourné : c'est −2.

L'intérêt de faire les choses de cette manière, c'est que tout marche de la
même manière : toutes les règles qu'on a apprises pour l'addition vont
marcher presque pareil pour la soustraction, il faut juste regarder quels
bouts sont à l'envers.

Il reste à expliquer ce qui se passe quand on a plusieurs soustractions,
comme dans « 4+5−6+7−8+9 ». La règle choisie est que le − ne retourne
que le nombre qui est immédiatement à sa droite, ici le 6 et le 8. Il faut
donc comprendre cette formule comme une addition de six termes, dont deux
sont à l'envers. On peut changer l'ordre, il faut juste garder les − devant
le 6 et le 8.

Bien sûr, ceci se combine avec les règles de priorité : 2−3×4+5 est
l'addition de trois termes, 2, 3×4 à l'envers et 5. Et on peut mettre des
parenthèses pour que le − agisse sur tout un groupe : 2−(3×4+5).

## Un petit mot sur la division

Tout comme la soustraction est une addition dont le second terme marche à
l'envers, la division est une multiplication dont le second terme marche à
l'envers. Mais du point de vue des notations, on a adopté une convention
différente : on représente la division par un trait horizontal, la « barre
de fraction ». Dans ce cas, la disposition de la formule ne laisse pas
d'ambiguïté sur le groupement des termes.

Il faut faire attention à ce que rien ne dépasse du trait de fraction. C'est
très important pour les − : soit un − est devant la fraction, et donc il
renverse l'ensemble de la fraction, et dans ce cas on est censé l'aligner
avec la barre de fraction elle-même ; soit un − est au début du numérateur
ou du dénominateur (respectivement le haut et le bas), et dans ce cas il est
à prendre avec le reste de ce bout de formule (et il risque de ne concerner
que son début). Un − à moitié sur et à moitié devant la fraction serait
ambigu, et à ce titre est strictement interdit.

```
  3+4
− ─── = − [(3+4) ÷ 5]
   5

−3+4
──── = [(−3)+4] ÷ 5
  5

− 3+4
  ─── ???
   5
```

Sur les calculatrices scientifiques (mais pas les modèles les plus récents,
qui dessinent les formules comme avec un stylo), la division se note avec /,
et dans ce cas ça marche par rapport aux × (qui sont souvent notés \*) comme
les − marchent par rapport aux + : le bout de formule immédiatement à droite
du / divise au lieu de multiplier. Dans le doute, mettre des parenthèses, la
calculatrice ne t'en voudra pas.

Pour bien assimiler tout ça, je pense qu'on peut procéder ainsi : inventer
une formule compliquée, dessiner les groupes avec des accolades ou des
patatoïdes, calculer les valeurs des différents morceaux jusqu'à avoir le
résultat global. Et pour finir, taper la formule dans une calculatrice et
regarder si elle est d'accord avec le résultat.

Recommencer jusqu'à ce qu'on y arrive facilement, jusqu'à ce que le cerveau
ait appris à voir la structure de la formule du premier coup d'œil.

## C'est quoi ces lettres ?

Avec toutes ces explications, on devrait pouvoir comprendre (2+3)×(5−4), ce
qui commence à ressembler à la formule de la question. Pour alléger les
notations, on se permet de ne pas écrire le ×, donc on peut écrire
(2+3)(5−4), c'est pareil. (On n'a évidemment pas le droit entre deux nombres
écrits en chiffres : 22 n'est pas la même chose que 2×2 !)

Mais il y a ce x qui nous embête. Que veut-il dire, d'où sort-il ?

Pour commencer, je tiens à souligner qu'on vous le dit, ce que c'est que ce
x : c'est le petit bout de phrase de l'énoncé dont vous ne tenez jamais
compte, « où x est un nombre réel quelconque ». Mais il va falloir y
revenir.

Un jour, peut-être, un mathématicien a remarqué que 2×(3+4) donne le même
résultat, 14, que 2×3+2×4, ce qu'on note avec un =. Et il a probablement
remarqué d'autres égalités :

- 3×(3+4) = 3×3+3×4
- 4×(3+4) = 4×3+4×4
- 5×(3+4) = 5×3+5×4
- 6×(3+4) = 6×3+6×4
- …

Il a généralisé, et il a communiqué sa découverte :
« [ ]×(3+4)=[ ]×3+[ ]×4 : mettez n'importe quel nombre, le même, dans les
trois cases, et l'égalité est vraie. »

Ça marche. Mais ensuite, il s'est rendu compte qu'on pouvait remplacer le 3
et le 4 par n'importe quel nombre, du moment qu'on met bien le même aux deux
endroits à chaque fois. Mais comment le communiquer ?
« [ ]×([ ]+[ ])=[ ]×[ ]+[ ]×[ ] » ? On ne voit plus quelles cases doivent
contenir le même nombre.

On pourrait utiliser des couleurs, mais ce n'est pas pratique, et
discriminatoire envers les daltoniens. On peut mettre un petit symbole dans
les cases, le même quand les cases doivent contenir le même nombre. Tant
qu'à faire, pas la peine d'inventer des symboles, on a déjà tout l'alphabet
à disposition. Et on peut arrêter d'imaginer que le lecteur va effectivement
écrire des nombres dans les cases, donc mettre juste la lettre, sans laisser
de place ni dessiner de cadre.

On en arrive donc, en prenant les trois premières lettres de l'alphabet, à
« a×(b+c)=a×b+a×c ». Ce qu'il faut comprendre, c'est qu'en mettant n'importe
quel nombre à la place des trois lettres, forcément le même quand c'est la
même lettre, on arrive à deux calculs qui donnent le même résultat de part
et d'autre du =.

Pour être rigoureux, il faut préciser ce que représentent les lettres. On
écrira par exemple « Pour tous nombres réels a, b, c, on a
a×(b+c)=a×b+a×c ». Ça permet de préciser par la même occasion quel genre de
nombres on a le droit de mettre : parfois, la formule ne marche qu'avec des
nombres positifs ou qu'avec des nombres entiers, c'est là qu'on l'indique.

Quand un exercice demande de démontrer une égalité entre deux formules, en
général, on s'attend à un raisonnement qui marche avec toutes les valeurs
possibles (et si ce n'est pas le cas, on le précise). Le faire sur un
exemple, ou même quelques uns, n'est pas suffisant. Il faut donc appliquer
des règles de calcul qui marchent à tous les coup. On les apprend en cours,
celle ci-dessus est un exemple.

## La simple distributivité

Cette formule que je viens d'évoquer a×(b+c)=a×b+a×c, qui est valable en
mettant à la place de a, b, et c n'importe quel nombre, et même plein de
trucs qui se comportent comme des nombres (ça marche si b et c sont des
vecteurs, par exemple), s'appelle la *distributivité de la multiplication
sur l'addition*, parce qu'en quelque sorte on a distribué la multiplication
par a aux deux termes de l'addition b et c.

Mais que veut dire cette formule exactement ? On peut la voir de plusieurs
manières, mais j'aime bien celle-ci :

```
     b          c
 ┌───────┬─────────────┐
 │       │             │
a│       │             │
 │       │             │
 └───────┴─────────────┘
```

On voit deux rectangles collés, tous les deux de hauteur a, et l'un de
largeur b, l'autre de largeur c (d'autres parlent de la longueur et la
largeur du rectangle, ne nous laissons pas enfermer dans les mots).
Calculons les aires. Pour un rectangle, elle se calcule en multipliant la
hauteur par la largeur. Donc l'aire du rectangle de gauche est a×b et celui
de droite fait a×c.

On peut aussi voir un seul grand rectangle de largeur b+c, donc d'aire
a×(b+c). Mais on peut choisir de la calculer en additionnant l'aire des deux
petits rectangles, ce qui donne a×b+a×c. Et comme c'est le même rectangle,
donc la même aire, ces deux nombres sont égaux.

Donc a×(b+c)=a×b+a×c.

Le raisonnement géométrique marche pour des longueurs, donc des nombres
réels positifs. Et les règles de calcul pour les autres sortes de nombres
sont choisies de sorte que que ça continue à marcher.

Mais il est bon d'avoir plusieurs formulations en tête. En particulier, la
formulation mécanique est intéressante : quand on a une multiplication avec
un des termes qui est une addition (ou une soustraction, on a vu que c'était
pareil), la multiplication est distribuée sur chacun des termes de
l'addition. On réécrit l'addition avec tous ses termes, mais en insérant la
multiplication dans chacun.

(Le paragraphe précédent est court, mais il est important, puisqu'il dit
comment faire le calcul en pratique.)

## Manipuler une formule

Nous savons maintenant que a×(b+c)=a×b+a×c pour tous nombres a, b, c. Mais
comment l'utiliser ?

Imaginons qu'on nous demande de simplifier 2x−3/x+(5(2x+4)−7)/3.

J'allais oublier de préciser : … où x est un nombre réel non nul quelconque.
Mais tu avais deviné.

Avec de l'habitude, on remarque qu'il y a une multiplication sur une
addition : 5(2x+4). Dit autrement, on reconnaît le membre de gauche de la
formule de simple distributivité, avec a↔5, b↔2x et c↔4 (↔ n'est pas un
symbole mathématique officiel). Et donc on sait que ce bout de formule peut
également s'écrire 5×2x+5×4.

Si on a deux fois le même nombre écrit de deux manières différentes, 5(2x+4)
et 5×2x+5×4, et qu'on fait le même calcul par dessus, on arrive au même
résultat. Or la formule de départ, c'est justement un calcul autour de
5(2x+4) ; donc on écrit le même calcul autour de 5×2x+5×4 et c'est égal.

2x−3/x+(5(2x+4)−7)/3 = 2x−3/x+(5×2x+5×4−7)/3

En pratique, on fait ça directement : on voit la situation de distributivité
à l'intérieur de la formule, on applique la transformation sur place, sans
toucher au reste. On peut y penser comme un échange standard en mécanique :
on enlève la pièce défectueuse, on met une pièce neuve à la place. Le reste
de la machine ne bouge pas.

Attention, il y a une double subtilité. Regardons la formule 2×5x+5t. On
voit 5x+5t, et on a envie de le transformer en 5(x+t). Mais ça ne marche
pas, parce que les groupes dans la formule de départ son (2×5x)+(5t), et que
pour isoler le 5x+5t il faudrait séparer le 5x du 2×, et donc changer la
structure de la formule. (Dans cet exemple, cependant, on peut réorganiser
les termes pour que ça marche ; mais le 2× ne sera pas devant.)

La même subtilité se produit dans l'autre sens : si on part de 3×7(u+v), on
a envie de remplacer 7(u+v) par 7u+7v. Mais si on écrit 3× devant, le 3× ne
sera collé qu'au 7u, pas au 7v. Il faut donc grouper 7u+7v, l'emballer dans
des parenthèses : 3×(7u+7v). Pour reprendre l'analogie avec la mécanique, il
faut que la pièce de rechange se tienne ; si elle est formée de plusieurs
morceaux qui ne tiennent pas bien ensemble, on l'attache avec une élastique
ou on la met dans une boîte.

## La double distributivité

On peut maintenant s'attaquer à la double distributivité, c'est à dire la
formule qui permet de simplifier (a+b)(c+d), où a, b, c, d sont quatre
nombres quelconques.

On peut essayer d'utiliser la même astuce géométrique que plus tôt : un
rectangle coupé à la fois en largeur et en hauteur, qui forme donc quatre
petits rectangles. (Essaye, et note la formule que tu trouves, tu pourras
vérifier si tu as la même à la fin.)

Mais je préfère montrer comment la retrouver par le raisonnement, pour la
relier au reste, de manière à ce que les différentes notions se soutiennent
les unes les autres dans ton esprit.

Donc, transformons (a+b)(c+d) : une formule où il y a une multiplication
dont *les deux* termes sont des additions.

On se rappelle la simple distributivité, qui parle des cas où une
multiplication a *un* terme qui est une addition. Si les deux termes sont
des additions, il suffit de faire semblant de ne pas voir que l'un des deux
en est une pour être dans la situation. Faisons semblant de ne pas voir que
a+b est une addition, traitons-le comme le a de la formule de la simple
distributivité.

En d'autres termes, nous allons distribuer la multiplication par (a+b) à
chacun des termes de l'addition c+d, ça donne : (a+b)×c+(a+b)×d.

Ce n'est pas fini. Regardons le bout de gauche, (a+b)×c : c'est encore une
situation de simple distributivité. On a échangé la gauche et la droite,
mais ce n'est pas grave puisque la multiplication est symétrique. On peut
donc l'écrire a×c+b×c, on a l'habitude. Pareil pour la droite : (a+b)×d est
pareil que a×d+b×d.

On remet le + qu'il y avait entre les deux, ça donne (a×c+b×c)+(a×d+b×d).
J'ai tenu à mettre les parenthèses parce que je colle deux formules entre
elles par une addition, il faut préserver la structure. Mais comme
l'addition est associative (cf. plus haut), ces parenthèses ne servent pas,
donc on termine avec a×c+b×c+a×d+b×d. Et on peut se passer des × :
ac+bc+ad+bd.

(Est-ce que c'est ce que tu avais trouvé avec la figure ? Ce n'est pas grave
si l'ordre n'est pas le même, c'est une addition.)

Rédigeons le calcul :

```
(a+b)(c+d) = (a+b)×c+(a+b)×d
           = (a×c+b×c)+(a×d+b×d)
           = ac+bc+ad+bd
```

Ce que disent ces =, c'est que les formules donnent le même résultat pour
toutes les valeurs de a, b, c, d. Et si la première est égale à la deuxième,
la deuxième à la troisième, la troisième à la quatrième, c'est qu'elles sont
toutes égales.

On a l'habitude d'aligner les = verticalement parce qu'implicitement, c'est
toujours la formule de départ, celle qui nous intéresse, qui est à gauche.
Quand elle est courte, par exemple juste « A= » ou « f(x)= », on peut la
remettre à chaque ligne.

Essayons de résumer la double distributivité en la décrivant par une
méthode : quand on a une multiplication entre deux additions, chaque terme
de la première addition se retrouve multiplié par chaque terme de la seconde
addition, et le tout est additionné.

Formulé ainsi, on peut l'appliquer même quand on a plus de termes :
(a+b+c+d)(e+f+g). Avec quatre termes à gauche et trois termes à droite, il y
aura 4×3=12 termes au total ; mais peut-être que certains vont se simplifier
ensemble à l'étape d'après.

Je fais exprès, à ce point, de ne pas évoquer la soustraction. On se
rappelle qu'une soustraction, c'est une addition dont le terme de droite
marche à l'envers : ça devrait suffire sans qu'il soit nécessaire
d'apprendre de nouvelle règle. Mais j'ai fait exprès de mettre une
soustraction dans l'énoncé, pour qu'on puisse vérifier qu'on a bien compris
comment les deux règles marchent ensemble.

## Résolvons l'exercice

On nous demandait de développer (2x+3)(5−4x). Développer, c'est faire sortir
les additions des parenthèses, donc appliquer la distributivité, simple,
double ou pire. Le contraire, c'est factoriser. La tâche de développer est
purement mécanique : on applique la technique, on arrive au résultat. Pour
factoriser, en revanche, il faut de la chance, il faut repérer qu'il y a
deux fois le même bout de formule, dans la bonne disposition, et des fois ce
n'est pas apparent. Ici, on doit développer, donc c'est facile, et ce n'est
que la double distributivité.

Attention, il y a un −. Comme je l'ai expliqué, je n'ai dit comment faire
qu'avec des +, mais un −, c'est comme un + qui retourne le terme
immédiatement à sa droite. Donc ici, 4x est à l'envers. Il sera toujours à
l'envers quand on aura développé, donc il y aura un − plutôt qu'un + devant
chacun des termes qui contiennent le 4x.

Ça nous donne :

(2x+3)(5−4x) = 2x×5 − 2x×4x + 3×5 − 3×4x

Il reste à simplifier : 2x×5, c'est une multiplication à trois termes, on
fait dans l'ordre qu'on veut, donc on commence par 2×5 qui fait 10, donc
10x. Pareil pour 3×4x qui devient 12x. Et pour 2x×4x, on fait 2×4=8 et on a
aussi x×x, dont on sait que ça peut s'écrire x². Donc :

(2x+3)(5−4x) = 10x − 8x² + 15 − 12x

C'est une addition, donc l'ordre des termes n'a pas d'importance, à
condition de se rappeler que le − concerne toujours le terme qui est juste à
sa droite.

Il reste une petite simplification, entre le 10x et le 12x (et le − qui va
avec, ne pas l'oublier !). Si tu as deux pommes plus trois pommes, ça fait
cinq pommes, 2+3=5, on additionne les pommes. On additionne les x pareil. Ou
on soustrait, toujours pareil.

On peut le faire rigoureusement : 10x−12x, c'est une situation de simple
distributivité, mais déjà sous la forme résultat, avec le x qui apparaît aux
deux endroits. Donc on peut faire le contraire de développer, factoriser :
10x−12x=(10−12)x. Et pour finir, on calcule 10−12.

Une formule comme ça, on aime bien mettre les termes dans l'ordre de la
puissance de x : d'abord les x², puis les x, puis la constante. S'il y avait
des x³, on les mettrait en premier.

Donc :

(2x+3)(5−4x) = − 8x² − 2x + 15

C'est ce que j'avais annoncé.

## Comment s'entraîner en pratique

J'espère que tu as tout compris. Maintenant, il faut savoir le faire en
toute circonstance, pour pouvoir compter dessus tout au long de l'année et
au delà.

D'abord, inventer une question : un terme avec un x, un terme constant, dans
l'ordre qu'on veut, un + ou un − entre les deux, des parenthèses autour ; un
deuxième groupe pareil. Ne pas prendre des nombres trop grands, pour pouvoir
les multiplier et additionner de tête.

Ensuite, faire le calcul, comme ci-dessus.

Enfin, vérifier. Par exemple avec une calculatrice graphique : écrire la
formule de départ dans la première fonction, le résultat dans la deuxième,
demander un tableau de valeur. Si les valeurs sont les mêmes, c'est juste,
sinon c'est faux.

Si c'est faux, chercher l'erreur, corriger.

Recommencer. Recommencer jusqu'à ne plus faire d'erreur. Normalement, à ce
niveau, tu devrais commencer à remarquer des choses. Essaie de les exprimer
avant de lire les exemples. Voici quelques éléments :

- Les nombres vont toujours se multiplier et rester à côté des x : autant
  les multiplier directement.

- On aura toujours un seul terme en x² : on peut le traiter en premier.

- On aura toujours un seul terme constant, sans x : on peut le traiter en
  dernier.

- On aura toujours deux termes en x : on peut les additionner directement.

(Il y a aussi quelque chose à remarquer quand il y a deux soustractions :
l'as-tu vu ?)

Quand c'est bien rentré, essayer de ne pas écrire toutes les étapes. Avec
l'habitude, tu devrais pouvoir arriver au résultat directement, de tête.
Pour ça, il ne faut pas forcément faire le calcul dans l'ordre où il vient,
mais plutôt dans l'ordre où on le veut : d'abord les termes qui vont donner
du x², puis les termes qui vont donner du x et enfin les constantes.

C'est comme ça que je mène le calcul en pratique : d'abord les x², donc le
2x avec le 4x, 2×4=8, attention il y a un −, donc −8x² ; puis les x, donc
2×5=10, 3×4=12, attention il y a un −, 10−12=−2, donc −2x ; enfin 3×5=15.

Attention, à chaque fois que tu fais une erreur, il faut recommencer.

Quand c'est bien rentré, il faut acquérir la vitesse. Je propose la démarche
suivante, à deux ou plus. Chacun invente dix énoncés et les écrit sur une
feuille. Vous échangez les feuilles, retournées. Puis, au signal, vous
lancez les chronomètres et vous calculez. Quand vous avez fini, vous arrêtez
les chronomètres.

Quand tout le monde a fini, vous ré-échangez les feuilles et vous vérifiez.

Pose-toi comme objectif de faire au maximum une petite erreur sur les dix,
le tout en moins de sept minutes. Si tu y arrives, tu te rendras compte que
tous les calculs en classe vont devenir beaucoup plus faciles.

En parallèle, il faut s'attaquer à des énoncés un peu plus compliqués, par
exemple avec des x² : (2x²+3x−5)(7x−2), et puis avec des fractions comme
nombres, et avec des x et des y, etc.

Cette démarche est lourde, au début. Mais les techniques de calcul, ce sont
les fondamentaux des mathématiques. On n'arrivera pas à résoudre un exercice
compliqué si on ne voit pas les simplifications au premier coup d'œil. En
contrepartie, si on a confiance en ses capacités à calculer, tout le reste
paraît plus simple. Il faut donc s'entraîner à ce point à chaque fois qu'une
nouvelle technique de calcul est apprise : résoudre les équations
quadratiques avec le discriminant, dériver un produit, etc. Chaque nouvelle
technique viendra plus facilement que la précédente.

## Conclusion

Je n'entends pas révolutionner l'enseignement des mathématiques, je suis
d'ailleurs souvent dubitatif vis à vis des révolutions, surtout celles
contre quelque chose qui marche déjà plutôt bien. Mon but est plus modeste :
souligner des points où il pourrait être légèrement amélioré.

L'intuition sur la structure d'une formule est quelque chose qui manque
beaucoup. Jamais dans ma scolarité on m'a dit qu'une formule mathématique
avait une grammaire qu'on pouvait analyser au même titre qu'une phrase. De
même, la plupart des analogies que j'ai développées ne m'ont pas été données
dans le cadre scolaire : soit je les ai inventées moi-même, soit je les ai
découvertes dans des articles de vulgarisation. Pourtant, elles aideraient
probablement beaucoup d'élèves, des élèves qui ont d'autres centres
d'intérêt que de lire des magazines consacrés aux maths.

C'est un peu une spécificité française, cette sorte de snobisme : on te
donne la recette théorique parfaite, et maintenant débrouille-toi. C'est
probablement ce qui a fait le succès du mouvement bourbakiste, certainement
une très bonne chose pour la rigueur des mathématiques pointues, mais
appliqué à l'enseignement ça a donné les « maths modernes », à beaucoup de
point de vue catastrophiques. On retrouve ce snobisme dans des domaines
complètement différents, par exemple la rareté des cours d'écriture
créative, comme si, au delà de la simple orthographe, il n'y avait pas des
techniques qu'on puisse apprendre et transmettre pour aider à construire une
bonne histoire.

Si je dois te donner un dernier conseil, cher élève imaginaire, c'est
d'essayer de vraiment bien comprendre un point précis du cours. Par exemple
la double distributivité avec les explications ci-dessus. De vraiment le
comprendre dans ses moindres détails, de persévérer, et de creuser les
points qui gardent de l'ombre. Ce noyau de compréhension pourra servir de
graine pour comprendre d'autres concepts voisins, et surtout pour construire
une confiance en soi.

Bon courage.


 [3b1b]: https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw/videos
 [wa]: https://www.wolframalpha.com/
