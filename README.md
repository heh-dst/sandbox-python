# sandbox-c

Espace d'expérimentation pour programmer en C et C++.

Ce conteneur de développement fournit un espace de travail sous Linux avec tous les outils et librairies nécessaires pour la programmation en C et C++.

Des outils de développement Python sont également installés pour pouvoir facilement comparer les versions en C ou C++ avec leur contrepartie en Python.

## Utilisation

1. Créez votre fichier source `monprogramme.c` (en C) ou `monprogramme.cpp` (en C++).
2. Compilez votre fichier
    ```
    make monprogramme
    ```
    Notez bien que l'argument de la commande `make` est le nom du fichier sans extension.
3. Exécutez votre programme
    ```
    ./monprogramme
    ```

## Exemples

### En C

```
make hello
./hello
```

### En C++

```
make hello++
./hello++
```

### En Python
```
python3 ./hello.py
```
