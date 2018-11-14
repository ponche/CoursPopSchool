# Le language C 

## les différent type de variable 

en C, il existe plusieurs type de variable 
voici les différent type de variable : 
- **int** est une type de variable qui peut stoker des nombre entier  
- **float** est une type de variable qui peut stocker des nombre à virgule 
- **long** est une type de variable  qui peut stocker un grand entier 
- **double** est une type variable qui peut stocker une grand nombre à virgule 
- **bool** est une type de variable qui peut prendre que deux état (true/false ) 
- **char** est une type de variable conçu pour stocker un caractère de la table ASCII 
- **void** est une type de variable ou on ne peut rien mettre ( c'est le néant ) 

## comment déclarer une variable en c 

pour déclarer une variable en c, il faut écrire le type suivi du noms de la variable, exemple : 
``` 
int maVariable ; 
``` 

ce code si dessous déclare une variable de type **int** qui a pour nom **maVariable**

## affecter une valeur à une variable 

pour affecter une valeur à une variable, il faut utiliser l'opérateur **=** 
exemple : 
```
maVariable = 69 ; 
```

dans cette exemple si dessous on affecte le nombre 69 dans la variable **maVariable** 

## déclarer une fonction en C 

![dino](http://remi-ponche.fr/source/dino-function.png)

les fonctions, c'est comme des dinossaure, tu lui donne quelque choses a manger (argument ) ensuite il te pond un truc ( return ) . 
voici comment on déclare une fonction : 
```
double surfaceRectangle(double longueur, double largeur) 
{
	return longueur * largeur  ; 
} 
```
dans cette exemple si dessous on déclare une fonction qui renvoie un **double** ( l'oeuf du dinossaure ) et prend 2 arguments (longueur, largeur ) . 
pour info, la déclaration des argument de fonction est identique au variable. 

**remarque :** si on veut crée une fonction qui ne renvoie rien, on utilise le type **void** ) 


## appel de la fonction 

une fonction non appelé ne sert a rien. ( sauf pour rendre le code déguellasse ) 
pour appeler du code il suffit juste d'écrire ça : 
```
double surfaceCuisine = surfaceRectangle( 30 , 60 ) ; 
```
dans le code si dessus on stocke le return de la fonction dans la variable *surfaceCuisine*
mais on n'est pas obliger de stocker la valeur, si on a pas besoin. et juste executer le code de la fonction 

## les structure de controle 

les structure de controle permet de faire prendre au programme des décision en fonction des condition 
voici un exemple de **if** sur la forme la plus simple : 
```
if ( condition ) 
{
	// code executuer si condition est égal à true 
}
``` 

avec un sinon  : 
``` 
if ( condition ) 
{
	// code executer si condition est égal à true 
}
else
{
	// code executer si condition non remplie ( egal a false ) 
}
```


