# Sommaire 
- [Sommaire](#sommaire)
- [Vous déplacer dans l'arborescence de vos fichiers](#vous-déplacer-dans-larborescence-de-vos-fichiers)
- [Qu'est-ce qu'un chemin ?](#quest-ce-quun-chemin-)
  - [Chemin absolu](#chemin-absolu)
  - [Chemin relatif](#chemin-relatif)
- [Qu'est-ce qu'un terminal ?](#quest-ce-quun-terminal-)
- [Vous déplacer dans un terminal](#vous-déplacer-dans-un-terminal)



# Vous déplacer dans l'arborescence de vos fichiers

<p align="justify"> 
Pour compiler un fichier, il vous est nécessaire d'indiquer son chemin. Dans votre ordinateur, les fichiers sont organisés en arborescence. Un dossier peut contenir d'autres dossiers et des fichiers. Comme illustré ci-dessous, l'organisation des dossiers peut être vu comme un arbre. Sur Linux et Mac OS, le dossier dit "racine", est le premier dossier, contenu par aucun autre dossier et se nomme "/". Pour Windows, il existe un dossier racine par disque monté et sont nommés avec la lettre associée au disque. Par exemple, "C://", "D://", "E://" etc. 
</p>


<p align="center"><img src="images/arborescence.png" alt="Exemple d'arborescence de fichiers" width="400"/></p>


<p align="justify"> 
Si vous avez utilisé un ordinateur sur Windows, vous vous êtes certainement déjà servi de ce que nous (les informaticiens) nommons un explorateur de fichiers. Le même type de logiciel est présent sur mac et dans la plus part des distributions linux modernes. Ce programme, présent nativement sur Windows, vous permet de naviguer dans l'arborescence de vos fichiers.
</p> 



<p align="justify">
Pour apprendre à vous déplacer dans les dossiers de votre ordinateur, nous aborderons dans cette sections les concepts d'arborescence et de chemin. De plus, nous introduirons aussi le terminal – ou invité de commande – pour vous apprendre à vous déplacer dans votre ordinateur grâce à des commandes. Ces connaissances et compétences vont seront d'une grande aide pour compiler vos projets de programmation mais également pour réaliser une très grand nombre, si ce n'est toutes, de tâches informatiques.
</p>




# Qu'est-ce qu'un chemin ?
Le chemin d'un fichier indique son positionnement dans la machine (ordinateur, serveur) que vous utilisez. Grâce au chemin d'un fichier, vous pouvez indiquer comment y accéder pour le lire, le modifier ou l'exécuter. 


## Chemin absolu

## Chemin relatif




# Qu'est-ce qu'un terminal ?

<p align="center"><img src="images/exemple_prompt_terminal.png" alt="Exemple de prompt de terminal" width="400"/></p>



# Vous déplacer dans un terminal

Sur Mac OS et sur Linux : 
```
cd [chemin du dossier]
```


Pour éviter d'avoir à écrire "change directory" à chaque commande, les développeurs ont préféré opter pour le diminutif "cd". 

Nous nommons "dossier courant" le dossier dans lequel vous vous trouvez dans un terminal ou dans l'explorateur de fichier. Pour vous aider à y voir plus clair, vous pouvez afficher les fichiers et dossiers présents dans votre dossier courant grâce à la commande suivante sur Linux et Mac OS : 
``` 
ls
```

Pour éviter d'avoir à écrire "list" à chaque commande, les développeurs ont cette fois-ci préféré opter pour le diminutif "ls". Vous pouvez aussi afficher le contenu d'un autre dossier : 
```
ls [chemin du dossier]
```

Sur Windows, le principe est le même mais le nom de la commande "dir". La structure est donc la suivante : 
```
dir [chemin du dossier]
```

Dans tout dossier, vous trouverez toujours deux sous-dossier, "." et "..". Le dossier "." fait référence au dossier courant. Le dossier ".." fait référence au dossier parent, le dossier précédent dans l'arborescence des fichiers. Par exemple, la commande `cd .` vous déplacera dans le dossier courant. D'une certaine manière, vous ne vous êtes donc pas déplacé en utilisant cette commande. Dans cet exemple, le sous-dossier "." n'a pas d'utilité mais il devient utile dans d'autres circonstances que vous rencontrerez plus tard. Plus intéressant à court terme, la commande `cd ..` vous permet de revenir dans le dossier parent. Je vous invite très fortement à la tester.

