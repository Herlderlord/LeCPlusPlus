
# Apprendre les bases du C++
Dans ce *book*, vous allez apprendre les bases du langage c++.

# Le code de base

Le code ci-dessous est un code basique qui, une fois exécuté, affiche la phrase "Hello World!".

```c++
#include<iostream>
using namespace std;

int main() {
    cout << "Hello world!" << endl;
    return 0;
}
```

Analysons ce code ligne par ligne : 
- `#include <iostream>` indique au compilateur qu'il devra utiliser la bibliothèque (*library* en anglais) *iostream*. Nous apprendrons plus tard ce qu'est une bibliothèque. Pour le moment, je vous invite à simplement copier coller cette ligne au début de chacun de vos programmes.
- `using namespace std` indique au compilateur que les fonctions et autres mots clefs que vous employez dans votre programme appartiennent éventuellement au *namespace std*. Nous verrons la notion de *namespace* plus tard.
- `main() { }` main est la fonction principale de votre programme. Lorsque vous demandez au compilateur de transformer votre code en programme exécutable, il recherche la fonction nommée "main", son nom est donc important. Tout ce qui est contenu entre les deux accolades, l'accolade ouvrante '{' et l'acolade fermante '}', sera exécuté, ligne après ligne et indiquera en conséquence le comportement de votre programme. Plus tard, nous aborderons les fonctions. Pour le moment, contentez-vous d'écrire la fonction main ainsi et d'y mettre votre code entre les accolades, '{}'. 
- `cout << "Hello world!" << endl;` est une instruction. Celle ligne indique au programme d'afficher le terme "Hello world!" dans la console. Le terme `endl` indique au compil
- `return 0;` est une instruction. Cette ligne indique que la fonction *main* doit retourner la valeur 0 une fois à la fin de son exécution. Nous en apprendrons plus sur le mot clef *return* lorsque nous étudierons le concept de fonction.


Note : si vous n'écrivez pas la ligne `using namespace std;` vous devrez ajouter le préfix `std::` à `cout` et à `endl`. La phrase sera donc `std::cout << "Hello world!" << std::endl;`. 

Note 2 : l'instruction `return 0;` n'est pas obligatoire. Je vous suggère tout de même de prendre la bonne habitude de l'ajouter à la fin de votre fonction. 


# Les instructions
En C++, les lignes présentes dans la fonction main (entre l'accolade ouvrante '{' et l'accolade fermante '}') sont des instructions et sont exécutées séquentiellement, c'est à dire les unes à la suite des autres et de haut en bas. 

Les instructions de base sont codées de la manière suivante en C++ :  
```[instruction];```

Un exemple : définitir et initialiser une variable entière nommée *a*  
```int a = 5;```

Un second exemple : afficher le texte "Hello World!"  
```cout << "Hello World!" << endl;```

# Des exercices

Vous trouverez dans le fichier [exercices.md](exercices.md) des exercices pour mettre en pratique ce que vous avez appris dans ce *book*. Une solution est donnée à chaque exercice. Si vous bloquez, n'hésitez pas à ouvrir une *issue* sur github pour que d'autres personnes puissent vous aider.


# Mots à retenir 
- Accolade ouvrante
- Accolade fermante
- Instruction
- Exécution séquentielle
- 