# cat

> Affiche et concatène le contenu d'un ou plusieurs fichiers.
> Plus d'informations : <https://www.man7.org/linux/man-pages/man1/cat.1.html>.

- Affiche le contenu d'un fichier sur la sortie standard :

`cat {{fichier}}`

- Concatène le contenu de plusieurs fichiers vers le fichier de destination :

`cat {{fichier1}} {{fichier2}} > {{fichier_de_destination}}`

- Ajoute le contenu d'un ficher à la fin du fichier de destination :

`cat {{fichier1}} {{fichier2}} >> {{fichier_de_destination}}`

- Numérote toutes les lignes affichées :

`cat -n {{fichier}}`

- Affiche les caractères non-imprimables ainsi que les caractères d'espacement (en utilisant le préfixe `M-` prefix si non-ASCII) :

`cat -v -t -e {{fichier}}`
