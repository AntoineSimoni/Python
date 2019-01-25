# Python

### A : Les trucs a savoir 
-C ; base de nombreux langages (C++, Java, JavaScript, PHP, go, Rust...)
	-langage haut niveau
	-langage impératif 
	-langage compilé : opérations textuelles, conversion assembleur, conversion binaire, création fichier exécutable

-historique : 
	-71-73 : création du C
	-78 : K&R
	-89 : C89 / 1re norme ANSI-C
	-99 : C99

-Il FAUT : éditeur de code, compilateur. Éventuellement, si possible, débugger, gestionnaire de versionns.

-règles de base :
	-fichiers *.c et *.h
	-ASCII pas étendu
	-LINUX : 20 M lignes de C => plusieurs fichiers => *.h
	-sensible a la casse
	-pas de règle de codage obligatoire (pas de tab, de comm, indentation)

commentaire : -(C89, C99) /*toto*/
	      -(C99) //toto
variables :
	-typées
	-nom : minuscules, majuscules, chiffres, underscore
	-Nom explicite
	-déclaration : donne un nom et un type : char a;
	-affectation : donne une valeur : a = 3;
	-initialisation : déclaration + affectation : char a = 3;

### B : Les bases
Le langage C est un langage compilé de haut niveau/imperatif.
Il a plus de 30 ans.
Normes C89 et C99 a connaitre.
outils indispensables: editeur de texte
               compilateur
                debugger 
C sensible a la casse

en C89 /* / 
C99 //        /  //   */

Les editeurs mettent en evidence les mots clés.
Les variables sont typé.
Les types aident le compilateur / aident a connaitre les valeurs des bits / sert au programmeur.

si une valeur est au dessus de la valeur max c'est les bit les plus faibles soit on fait modulo 

un char a une valeur indeterminé max car on cest pas su c signed pu pas

### C : Les signes : 
Types:     signé = + ou -
    non signé = +

virgule fixe si pas de FPU

Virgule flottante = IEEE 754
    -float : 32bit   10^38
    -double : 64bit  10^308
    -précision finie Pi n'est pas stockable

Unsigned Char = 8 bits / 0 à -128
Unsigned Short >= 16 bits / 0 à -2^15
Unsigned long >= 32 bits / 0 à -2^31
Unsigned long long > 64 bits / 0 à -2^63


### D : Suffixes / préfixes

SUFFIXES 
	50 /*sabs suffixe, int */
	50u /* unsigned int */
	50U /* unsigned int */
	50l /* long */
	50L /* long */
	50ul /* unsigned long */
	50UL /* unsigned long */
	50uL /* unsigned long */
	50Ul /* unsigned long */


