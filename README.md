# 🐶 Estudo de Orientação a Objetos — Pet Machine

Projeto de estudo de **Programação Orientada a Objetos em Java**: uma máquina de banho para pets controlada por um menu no terminal.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

## ✨ Funcionalidades

- Colocar e retirar um pet da máquina
- Dar banho no pet (consome água e shampoo)
- Abastecer a máquina com água e shampoo
- Verificar os níveis de água e shampoo
- Verificar se há um pet no banho
- Limpar a máquina

## 🗂️ Estrutura

| Arquivo | Responsabilidade |
|---|---|
| [`src/Main.java`](src/Main.java) | Menu interativo e leitura das opções do usuário |
| [`src/PetMachine.java`](src/PetMachine.java) | Regras da máquina: água, shampoo, limpeza e banho |
| [`src/Pet.java`](src/Pet.java) | Representa o pet (nome e se está limpo) |

## ▶️ Como executar

```bash
cd src
javac *.java
java Main
```

Ou abra a pasta no IntelliJ IDEA e execute a classe `Main`.

## 🧠 Conceitos praticados

- Classes, objetos e construtores
- Encapsulamento (atributos `private`, getters e setters)
- Responsabilidade de cada classe
- `switch` com expressões lambda (`case 1 -> ...`)
