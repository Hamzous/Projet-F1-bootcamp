PARTIE PYTHON : 

- 1 :
on enlève les espaces
si c’est vide, on renvoie None
on sépare les minutes et les secondes
on convertit le temps en secondes
et on arrondit à 3 chiffres après la virgule

2:
on lit le fichier ligne par ligne
on saute l’en-tête
on sépare les valeurs avec ;
on récupère les infos de chaque pilote
si le pilote a abandonné, on met la position à 0 et le temps à None
sinon on convertit la position et le meilleur tour
et on stocke le résultat dans une liste

3 : 
on ouvre le fichier en écriture 
on écrit l’en-tête
on parcourt les résultats
si le temps est None, on laisse la valeur vide
sinon on met le temps avec 3 chiffres après la virgule
on écrit chaque ligne avec les valeurs séparées par ;
