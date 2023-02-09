
# Exercice 1

De combiens d'instructions est composée la fonction *main* dans le code suivant ?

```c++
#include<iostream>

using namespace std;

int main() {
    cout << "Hello World! " << endl;

    int a = 10;

    cout << "Hello" << a << endl;
    return 0;
}
```


# Exercice 2

Le code suivant fonctionne-t-il ?

```c++
#include<iostream>

int main() {
    std::cout << "Hello World! " << std::endl;

    int a = 10;

    std::cout << "Hello" << a << std::endl;
    return 0;
}
```



# Exercice 3

Essayez de compiler ce code. Vous remarquerez que ce n'est pas possible, le compilateur vous informera d'ailleurs qu'il y a une erreur dans le code. Quelle est-elle ?

```c++
#include<iostream>

int main() {
    std::cout << "Hello World! " << std::endl

    int a = 10;

    std::cout << "Hello" << a << std::endl;
    return 0;
}
```


