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



PARTIE JAVA :
1 :
on regarde la position du pilote
si il est dans les 10 premiers, on lui donne les points correspondants
si il a abandonné ou qu’il est au-delà de la 10e place, on met 0 point
2 :
on parcourt toutes les lignes
on cherche si le pilote existe déjà dans la liste
si il existe pas, on le crée
on ajoute ses points selon sa position
si il finit 1er, on ajoute une victoire
si il finit 2e, on ajoute une deuxième place
ensuite on trie par points, puis victoires, puis deuxièmes places, puis par nom  
3 :
on parcourt la liste des pilotes
on cherche si l’écurie existe déjà
si elle existe pas, on la crée
on additionne les points, les victoires et les deuxièmes places des pilotes de la même écurie
ensuite on trie pareil que pour les pilotes


PARTIE Javascritp : 
1 :

on crée une copie avec [...liste]
comme ça on modifie pas la liste de base
on trie par points du plus grand au plus petit
si les points sont égaux, on regarde les victoires
puis on renvoie la nouvelle liste

2 :
on récupère le <tbody> avec son id
on vide son contenu avec innerHTML = ""
on parcourt la liste
on crée une ligne <tr>
on ajoute data-nom
on met les 5 cellules dans l’ordre demandé
on ajoute la ligne dans le tableau

3 (pas terminé) : 
on récupère le <tbody>
on récupère toutes les lignes <tr>