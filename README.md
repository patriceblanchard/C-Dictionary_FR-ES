## C-Dictionnaire_FR-ES  


__Compilation et exécution :__  

gcc -Wall dico.c
a.out echantillon-test  


Exemple d'utilisation :  


Dictionnaire Français-Espagnol  

Saisir un mot à traduire :
absolutisme

Mot Français : absolutisme - Catégorie : [n]

Mot Espagnol : absolutismo - Catégorie : [n]

(Continuer : O/N):
n


__Exécution de deux tests :__

gcc -Wall -DTEST dico.c

La commande ci-dessus affichera :

Test1 : Imprimer les mots français dans un fichier
Impression des mots en français dans le fichier mot_fr.txt terminée.

Test2 : Rétroconstruction du fichier initial
Rétro-construction dans le fichier retro_construction.txt terminée.