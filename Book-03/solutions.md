
# Note introductive
Pour chaque exercice, vous trouverez des solutions qui ne sont pas affichées par défaut et que vous pouvez décider d'afficher individuellement. 



# Solutions
<details>
  <summary>Exercice 1</summary>
  
  Les instructions basiques en C++ sont séparées par des point-virgules. Dans le code de l'exercice 1, la fonction *main* est composée de 4 instructions.
  
  La première instruction est la suivante : 
  ```c++
  cout << "Hello World! " << endl;
  ```
    
  La seconde instruction est la suivante : 
  ```c++
  int a = 10;
  ```
    
    
  La troisième instruction est la suivante : 
  ```c++
  cout << "Hello" << a << endl;
  ```
    
  Enfin, la quatrième et dernière instruction est la suivante : 
  ```c++
  return 0;
  ```
  
</details>




<details>
  <summary>Exercice 2</summary>
  

  Oui, le code fonctionne. La ligne `using namespace std;` a été supprimée mais le préfix `std::` a été ajouté à tous les mots clefs `cout` et `endl`. 

  Par exemple, la ligne : 
  ```c++
  cout << "Hello World! " << endl;
  ```

  a été remplacée par la ligne suivante : 
  ```c++
  std::cout << "Hello World! " << std::endl;
  ```


</details>




<details>
  <summary>Exercice 3</summary>



  Une erreur est présente dans le code fourni par l'exercice trois. Un point virgule manque à la fin de la ligne `std::cout << "Hello World! " << std::endl`. Si vous essayez de compiler le programme, le compilateur va vous afficher la phrase suivante : 

  ```
  [NOM DE VOTRE FICHIER CPP]:4:46: error: expected ';' after expression
  std::cout << "Hello World! " << std::endl
  ```

  Prenons le temps de décortiquer l'erreur. Tout d'abord, le compilateur vous indique où votre erreur se trouve : `[NOM DE VOTRE FICHIER CPP]:4:46:`. Ici, le compilateur vous signifie que l'erreur se trouve dans le fichier `[NOM DE VOTRE FICHIER CPP]` à la ligne 4, et au caractère 46 de cette même ligne.

  Ensuite, le compilateur vous informe qu'il a trouvé une erreur et qu'il attendait un caractère ';', `error: expected ';' after expression`. 

  Finalement, il vous affiche la ligne où il a trouvé l'erreur pour éventuellement vous faire gagner du temps. 
    `std::cout << "Hello World! " << std::endl`. 

  Vous l'aurez donc compris, il manque bel et bien un point virgule à la fin de cette ligne. Je vous invite à l'ajouter et à compiler à nouveau. Aussi, n'hésitez pas à créer vous-même des erreurs dans le code et à compiler. Vous vous familiariserez aux différentes erreurs que vous pouvez rencontrer. (par exemple, enlevez des chevrons "<<" ou des "std").


</details>
