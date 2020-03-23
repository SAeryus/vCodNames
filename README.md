# vCodNames
holi

The structure of the repo is divided by the languages, the main folder for the the extra dictionaries is "WordCategories" and inside of it each language supported will be in a separate folder.

the categories inside each langueage folder will be store in plain ".m" files containing just the list of strings. The name of the category files can consist of word characters, digits and dashes and underscores.(here is the regex "^[\w-]+\.m")

*******************
--/WordCategories/
----/English/
------Cat1.m
----/Spanish/
------Cat1.m
------Cat2.m
.
.
.
----/LanguageXX/
------Cat1.m
.
.
.
*******************


example category file:

$ cat Prueba.m
$ {"Holi", "Boli", "Tato", "Hernan"}


