# Sommaire 
- [Sommaire](#sommaire)
- [Avant de lancer son premier programme](#avant-de-lancer-son-premier-programme)
- [Langues compilés](#langues-compilés)
- [Différence entre les Languages compilés et interprétés](#différence-entre-les-languages-compilés-et-interprétés)
- [Les logiciels pour compiler du C++](#les-logiciels-pour-compiler-du-c)
  - [Utiliser un éditeur de texte et un compilateur (recommandé pour apprendre)](#utiliser-un-éditeur-de-texte-et-un-compilateur-recommandé-pour-apprendre)
  - [Utiliser un IDE](#utiliser-un-ide)
- [Pourquoi je ne recommande l'usage d'un IDE pour apprendre à programmer](#pourquoi-je-ne-recommande-lusage-dun-ide-pour-apprendre-à-programmer)
- [Compiler son premier fichier](#compiler-son-premier-fichier)
  - [Sur Windows](#sur-windows)
    - [Installer mingw](#installer-mingw)
    - [Ajouter mingw dans la variable PATH](#ajouter-mingw-dans-la-variable-path)
  - [Sur Mac OS](#sur-mac-os)
  - [Sur Linux](#sur-linux)
- [Terminologie](#terminologie)
- [Pourquoi travailler sur l'éditeur de texte ?](#pourquoi-travailler-sur-léditeur-de-texte-)


# Avant de lancer son premier programme
Dans le book-0, vous avez appris à créer un fichier texte contenant votre code c++. Dans ce book, nous allons apprendre à exécuter un programme à partir d'un code C++. Nous verrons notamment comment compiler un fichier C++, étape indispensable avant d'exécuter le programme résultant. Comme d'habitude, différentes notions sont introduites avant de passer à la pratique. Si vous bloquez sur ces notions, n'hésitez pas à passer à la partie suivante, vous comprendrez certains concepts à force de pratique. Ayez confiance en la puissance d'apprentissage de votre cerveau. 😊

# Langues compilés
# Différence entre les Languages compilés et interprétés
Un langage de programmation est ... Parmi les langages de programmation, nous pouvons discerner deux types de langages :
- **Le language compilé (e.g. c++) :** le code est d'abord compilé/transformé en langage machine, un fichier binaire que votre machine peut exécuter. Le fichier résultant peut ensuite être exécuté par votre machine.
- **Le langage interprété (e.g. python) :** le code est lu ligne par ligne par un interpréteur qui transforme "à la volée" votre code en langage machine.


# Les logiciels pour compiler du C++
Pour compiler un projet, c'est à dire un ensemble de fichiers formant un programme, nous pouvons identifier deux méthodes. La première consiste à utiliser un éditeur de texte, à enregistrer vos fichiers au format c++ et à les compiler à l'aide d'un compilateur. Le second consiste à utiliser ce que nous nommons un IDE (Integrated Development Environment). Les deux méthodes sont présentées ci-après. Aussi, il y est expliqué pourquoi nous allons utiliser la première.


## Utiliser un éditeur de texte et un compilateur (recommandé pour apprendre)


## Utiliser un IDE
Comme énoncé plus tôt, un IDE est un *Integrated Development Environment*, en français, un environement de développement « intégré » (EDI). L'objectif de ces logiciels est de faciliter la vie du développement. Ainsi, tous les outils dont ils a besoin sont réunis dans un seul et même programme. Ainsi, vous trouverez dans un IDE des outils de *profiling*, *debugging*, *versioning*, etc. Vous y trouverez bien sûr aussi un éditeur de texte avec de la coloration syntaxique et des aides écrire votre code, notamment ce que nous nommons l'auto-complétion.

Si vous êtes curieux et que vous souhaitez découvrir des IDE, voici une petite liste d'exemples non exhaustive :
- **Visual Studio : ([site officiel](https://visualstudio.microsoft.com/fr/))** Est adapté pour coder en C++ ou C# (et en d'autres langages). 
- **Visual Studio Code : ([site officiel](https://code.visualstudio.com))** Il peut être vu comme un IDE mais il est généralement considéré comme un éditeur de texte modulable. 
- **CLion : ([site officiel](https://www.jetbrains.com/fr-fr/clion/))** La gamme d'IDE de JetBrains permet de coder dans de nombreux langages. Leur programme CLion est spécialisé dans la programmation en C++.  

# Pourquoi je ne recommande l'usage d'un IDE pour apprendre à programmer
Les IDE sont très utiles pour les programmeurs/codeurs. Ils leur font gagner du temps et rendent leur travail plus fluide et agréable. CEPENDANT, les IDE cachent énormément de mécanismes à l'utilisateur. Notamment, en C++, les étapes de compilation et d'exécution sont complètement opaques – ou du moins difficiles d'accès pour les néophytes. Si vous apprenez à programmer avec un IDE, vous allez passer à côté de nombreux concepts de bases et vous vous sentirez impuissants face à certaines erreurs que vous rencontrerez.





# Compiler son premier fichier
Pour compiler votre fichier, vous allez avoir besoin d'un compilateur de code c++. La démarche vous est expliquée ci-dessous.

## Sur Windows
### Installer mingw
TODO: Expliquer comment télécharger et installer mingw
### Ajouter mingw dans la variable PATH
TODO: Expliquer comment ajouter le bin de mingw dans la variable PATH

## Sur Mac OS 
TODO: Expliquer comment installer le compilateur c++ sur mac os. Différence avec les arch64 ?

## Sur Linux 
TODO: Expliquer comment installer le compilateur c++ sur linux.


# Terminologie
- Langage de programmation : 
- Language compilé : 
- Language interprété : 
- Compilateur : 
- Interpréteur : 





# Pourquoi travailler sur l'éditeur de texte ?
Pour des raisons pédagogiques, il est mieux de commencer à travailler sur un éditeur de texte. Les éditeurs de texte sont généralement moins complets que les IDE mais ils sont déjà pas mal.
Je vous propose ici de travailler avec un éditeur de texte simple, sans ce que nous nommons la coloration syntaxique ou autre. Pourquoi ? Il n'est pas intelligent, il ne va pas faire des choses à votre place et vous allez vraiment comprendre l'ensemble des mécanismes qui permettent de compiler un projet C++. Sans cela, un jour vous allez avoir certains bugs et vous serez incapables de comprendre comment le résoudre, pourquoi vous l'avez résolu (si vous trouvez des astuces sur le Web) etc.
Créer son premier fichier en c++. 

Dans ce premier cours, il va falloir mettre différents.