# cpp-test-repo

Ce projet est un exemple simple en C++ qui affiche "Hello, World!" dans la console.

## Structure du projet

```
cpp-test-repo
├── src
│   └── main.cpp      # Code source principal
├── CMakeLists.txt    # Fichier de configuration CMake
└── README.md         # Documentation du projet
```

## Compilation et exécution

Pour compiler et exécuter le programme, suivez ces étapes :

1. Assurez-vous d'avoir CMake et un compilateur C++ installés sur votre machine.
2. Ouvrez un terminal et naviguez jusqu'au répertoire du projet.
3. Exécutez les commandes suivantes :

```bash
mkdir build
cd build
cmake ..
make
```

4. Une fois la compilation terminée, exécutez le programme :

```bash
./src/main
```

Vous devriez voir le message "Hello, World!" affiché dans la console.

## Tests avec Docker

Ce projet est compatible avec les tests Docker. Vous pouvez exécuter les tests en utilisant la commande suivante :

```bash
sudo docker run project-c sh -c "find /usr/src/myapp -type f -executable -exec echo 'Executable found: {}' \\;"
```

Cela détectera les fichiers exécutables dans le répertoire du projet.