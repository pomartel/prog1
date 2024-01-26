+++
title = "Langages compilés vs langages interprétés"
+++

Les langages de programmation peuvent être classés en deux grandes catégories en fonction de leur mode d'exécution : compilés et interprétés. Voici les principales différences entre eux :

### Langages Compilés :
- **Compilation** : Dans les langages compilés, le code source est transformé en code machine (un format compréhensible par le processeur de l'ordinateur) à travers un processus appelé compilation. Cette étape est réalisée avant l'exécution du programme.
- **Exécution** : Une fois compilé, le code peut être exécuté directement par le système d'exploitation. Il n'a pas besoin de l'interpréteur pendant l'exécution.
- **Performance** : Les programmes compilés ont tendance à être plus rapides car la conversion du code en code machine est faite une seule fois avant l'exécution.
- **Portabilité** : Le code compilé est spécifique à un type de système d'exploitation et d'architecture matérielle. Pour exécuter le même programme sur différents systèmes, il doit être recompilé pour chaque système.
- **Exemples de langages** : C, C++, Go, Rust.

### Langages Interprétés :
- **Interprétation** : Dans les langages interprétés, le code source est exécuté ligne par ligne par un interpréteur. Il n'est pas converti en code machine à l'avance.
- **Exécution** : Chaque instruction est lue, analysée, puis exécutée directement. Ce processus se répète pour chaque ligne du programme.
- **Performance** : La performance peut être plus lente comparée aux langages compilés, car l'interprétation se fait en temps réel.
- **Portabilité** : Les programmes écrits dans des langages interprétés sont plus portables, car ils peuvent être exécutés sur n'importe quel système disposant de l'interpréteur approprié, sans nécessiter de recompilation.
- **Exemples de langages** : Python, JavaScript, Ruby.

Il est important de noter qu'il existe des langages qui peuvent être à la fois compilés et interprétés, en fonction de l'environnement ou du mode d'exécution. Par exemple, Java utilise un compilateur pour transformer le code source en bytecode, qui est ensuite interprété ou compilé en code machine au moment de l'exécution par la machine virtuelle Java (JVM). De même, certains environnements pour des langages traditionnellement interprétés comme Python offrent des options de compilation pour améliorer la performance.