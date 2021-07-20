# Moteur Physique en C++ avec SFML

Ce projet a été réalisé pour conclure la 1ère année de Bachelor en Games Programming à la SAE Institute. Il était le dernier projet à rendre dans le cadre du module gpr4400, le travail consistait a coder une partie d'un moteur physique 2D de manière à pouvoir observer des collisions crédibles entre plusieurs objets.

### Introduction

Etant novice en C++ et peu à l'aise en maths, moi et mes camarades avons grandement sollicité l'aide du professeur ainsi que de Ludo et André parfois. Si les mathématiques appris au lycée revenaient assez facilement, il y avait de nombreuses formules complexes dont l'explication nous échappait totalement, heureusement, on peut assez facilement retrouver sur wikipedia et internet les formules a appliquer pour un peu que l'on sache ce que l'on veut faire.

Voici le lien du repertoire Git avec mon moteur physique : https://github.com/SAE-Institute-Geneva/GPR4400_920_Cpp/tree/Victor3

### Maths, Physique, et implémentations

Le plus étonnant pour moi a été de réaliser a quel point implémenter un théorème de mathématique ou physique nécessite une compréhension élevé de celui-ci. 

Dans les cas les plus simples il suffit de copié-collé une formule puis la modifier en structurant le tout selon les règles du C++. (Exemple MRUA)

![MRUA](https://user-images.githubusercontent.com/70535416/126387093-8561645a-1d23-4824-a89e-b1327331a5fa.PNG)

Il y a aussi les vecteurs qui selon moi sont une bonne façon de se réhabituer au C++ avec des bouts de codes simples et un fonctionnement pas trop compliqué.

![Vector2](https://user-images.githubusercontent.com/70535416/126387478-d9646ce6-f944-42a0-a445-71b43ea76fd1.PNG)

Il y avait des choses plus compliquées telles que les matrices qui, certes, ne sont qu'un amas de formules à rallonge, mais totalement nouvelles pour la plupart d'entre nous et par conséquent très difficiles à assimiler.

![Matrix1](https://user-images.githubusercontent.com/70535416/126387806-1b005627-a9df-4ec2-928d-3b15b28dd727.PNG)

![Matrix2](https://user-images.githubusercontent.com/70535416/126387850-dfda5c7e-4cae-45ad-8346-d75818e47a46.PNG)

Cela a été très intéressant également de coder les différentes formes (cercle/ carré) ainsi que d'appliquer la physique avec un rigidbody. 

![Rigidbody](https://user-images.githubusercontent.com/70535416/126388105-361b714e-7e7f-4f25-ba31-632940fd3ccd.PNG)

La fonction Simulate qui est censé faire fonctionner la physique en la simulant a intervalle régulière reste encore aujourd'hui le plus grand point d'interrogation pour moi, je n'ai vraiment pas compris. Egalement, l'implémentation d'une Grid sur l'idée du Quadtree permettant de réduire le nombre de collisions à calculer nous a semblé extrêmement compliqué et nous avons été parfaitement incapable de le faire.

![Simulate](https://user-images.githubusercontent.com/70535416/126388333-334696f7-1d56-4fb1-890e-8db94b9ae296.PNG)

Ensuite, malgré toute la difficulté que j'ai a comprendre SFML, cela fait un bien fou de voir son travail récompensé avec les premières formes qui apparaissent dans la fenêtre.
Voici ce qu'on peut observer au final quand les collisions fonctionnent :

![ezgif com-gif-maker](https://user-images.githubusercontent.com/70535416/126389286-9412fb59-8822-466f-89b7-8d51b9c683ec.gif)


### Conclusion

Enfin, le plus difficile est toujours d'être livré à soi-même sans l'aide du professeur. Le combat contre le C++ est une lutte de tous les instants car les erreurs affichées par le compilateur sont souvent incompréhensible et bien trop vagues, la moindre petite erreur à un endroit peut en entraîner 100 autres, les copié-collés sont également la pire chose à faire en C++ et font souvent perdre plus de temps qu'autre chose. Pour ma part, je pense avoir perdu énormément de temps sur la compréhension de l'organisation d'un projet C++, ce qui m'a fait certes énormément progressé mais il m'arrive encore de faire les mêmes erreurs et de passer plusieurs heures avant voir le problème.
