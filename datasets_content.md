- data : all

- cdata : (2000 - 2030) avec au moins 5 val sur la période 2010-2017.

- bdata : data juste entre 2000 et 2030

- rdata : 
    - vient de data
    - contient toutes les lignes concernant les 13 indicateurs choisis (car dans cdata) ou contenant des mots clés comme computer.
    - d'abord entre 2000-2030, puis limité à 2000-2016 car pas d'info.
    - dropna(thresh=3 (au moins une val numérique)) sur les rows
    - filtré retirer les régions.

- 13 dataframes, un par indicateur.

- Traitement du premier, et en cours sur le deuxième.

