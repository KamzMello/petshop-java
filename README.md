# 🐾 Petshop Java

Projeto desenvolvido em **Java** com o objetivo de praticar conceitos de **Programação Orientada a Objetos (POO)** por meio da simulação de um sistema de gerenciamento de um Petshop.

A aplicação funciona via terminal e permite cadastrar animais, consultar informações, organizar uma fila de atendimento e executar serviços.

## 🚀 Funcionalidades

- Cadastro de pets (nome, espécie, peso e porte).
- Listagem dos animais cadastrados.
- Busca de pets pelo nome.
- Identificação das espécies cadastradas.
- Organização da fila de banho.
- Execução de serviços de banho, tosa e consulta.
- Comportamentos específicos para cachorros e gatos.
- Tratamento de exceções para entradas numéricas.

## 🛠️ Tecnologias e conceitos utilizados

- Java
- Programação Orientada a Objetos (POO)
- Classes e objetos
- Encapsulamento
- Herança e polimorfismo
- Interfaces
- ArrayList
- HashSet
- ArrayDeque
- Scanner
- Tratamento de exceções

## 📂 Estrutura do projeto

```text
petshop-java/
├── Banho.java
├── Cachorro.java
├── Consulta.java
├── Gato.java
├── Pet.java
├── Petshop.java
├── Servico.java
└── Tosa.java
```

## ▶️ Como executar

**Pré-requisito:** JDK instalado.

Clone o repositório:

```bash
git clone https://github.com/KamzMello/petshop-java.git
```

Entre na pasta do projeto:

```bash
cd petshop-java
```

Compile os arquivos:

```bash
mkdir -p out
javac -d out *.java
```

Execute a aplicação:

```bash
java -cp out petshop.Petshop
```

## 📌 Observações

- Os dados são armazenados em memória durante a execução.
- Projeto desenvolvido com finalidade educacional e prática de Java.

## 👩‍💻 Autora

**Camila Mello**

[GitHub – KamzMello](https://github.com/KamzMello)
