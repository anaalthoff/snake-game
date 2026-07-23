# Snake Game

Implementação do clássico jogo **Snake** desenvolvida em **Java**, utilizando a biblioteca **Lanterna** para renderização em terminal e aplicando conceitos de **Programação Orientada a Objetos**, **arquitetura MVC**, **testes automatizados** e **modelagem UML**.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white)


#  Sobre o projeto

Este projeto consiste na implementação do tradicional jogo **Snake**, desenvolvido como atividade acadêmica com o objetivo de aplicar conceitos de desenvolvimento de software utilizando Java.

O jogo foi construído utilizando a biblioteca **Lanterna**, permitindo a criação de interfaces gráficas diretamente no terminal. Durante o desenvolvimento foram explorados conceitos como orientação a objetos, arquitetura MVC, gerenciamento de eventos, modelagem UML e testes automatizados.

Além da implementação do jogo, o projeto inclui documentação, diagramas UML e uma suíte de testes para validar os principais componentes da aplicação.

# Funcionalidades

- Controle da cobra por teclado
- Crescimento da cobra ao consumir alimentos
- Geração aleatória de comida
- Sistema de pontuação
- Detecção de colisão com paredes
- Detecção de colisão com o próprio corpo
- Tela de Game Over
- Reinício da partida
- Interface em terminal utilizando Lanterna

# Arquitetura

O projeto foi desenvolvido seguindo o padrão **MVC (Model-View-Controller)**.

```text
Entrada do usuário
        │
        ▼
 Controller
        │
        ▼
    Model
        │
        ▼
     View
        │
        ▼
 Biblioteca Lanterna
```

# Estrutura do projeto

```text
src
├── main
│   └── java
│       ├── controller/
│       ├── gui/
│       ├── model/
│       ├── states/
│       ├── viewer/
│       ├── Application.java
│       └── SnakeGame.java
│
└── test
    └── java
        ├── controller/
        ├── model/
        └── ...
```

Além do código-fonte, o projeto também possui:

```text
docs/
├── imagens/
├── UML/
└── relatórios de testes
```

# Tecnologias utilizadas

- Java
- Gradle
- Lanterna
- JUnit

# Como jogar

O objetivo é controlar a cobra, coletando alimentos para aumentar sua pontuação e tamanho.

A partida termina quando a cobra:

- colide com uma parede;
- colide com o próprio corpo.

Após o Game Over, o jogador pode reiniciar ou encerrar a partida.

# Conceitos aplicados

Durante o desenvolvimento foram utilizados conceitos como:

- Programação Orientada a Objetos
- Arquitetura MVC
- Encapsulamento
- Polimorfismo
- Separação de responsabilidades
- Tratamento de eventos
- Game Loop
- Estruturas de dados
- Testes unitários
- Modelagem UML

# Como executar

## Clone o repositório

```bash
git clone https://github.com/anaalthoff/snake-game.git
```

## Entre na pasta

```bash
cd snake-game
```

## Execute a aplicação

Linux/macOS

```bash
./gradlew run
```

Windows

```bash
gradlew.bat run
```

# Testes

Os testes automatizados podem ser executados com:

```bash
./gradlew test
```

# Demonstração

O projeto possui imagens ilustrando:

- Gameplay
- Crescimento da cobra
- Tela de Game Over
- Relatórios de testes
- Diagramas UML

As imagens estão disponíveis na pasta:

```text
docs/imagens/
```

# Objetivos de aprendizagem

Este projeto foi desenvolvido para praticar:

- Desenvolvimento de jogos em Java
- Programação Orientada a Objetos
- Arquitetura MVC
- Testes automatizados
- Modelagem UML
- Organização de projetos Gradle
- Separação entre lógica de negócio e interface
- Boas práticas de engenharia de software
