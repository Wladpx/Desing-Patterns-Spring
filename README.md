# Design Patterns com Java: Dos Clássicos (GoF) ao Spring Framework

Este projeto demonstra a implementação de padrões de design clássicos (GoF) e sua aplicação com o Spring Framework.

## Descrição

O objetivo deste projeto é fornecer exemplos claros e práticos de como utilizar padrões de design clássicos (GoF) em Java, bem como mostrar como esses padrões podem ser aplicados e integrados utilizando o Spring Framework. O projeto inclui implementações de padrões como Singleton, Factory Method e Strategy, tanto em sua forma pura quanto em uma versão Spring.

## Ferramentas Utilizadas

- **Java 17**: Linguagem de programação utilizada para o desenvolvimento do projeto.
- **Spring Boot 2.5.4**: Framework utilizado para facilitar a criação de aplicações Java robustas e de fácil manutenção.
- **Maven**: Ferramenta de gerenciamento de dependências e automação de build.
- **VSCode**: IDE escolhida para o desenvolvimento do projeto devido à sua flexibilidade e vasta gama de extensões.

## Estrutura do Projeto

design-patterns-java
│
├── src
│ ├── main
│ │ ├── java
│ │ │ └── com
│ │ │ └── example
│ │ │ └── designpatterns
│ │ │ ├── gof
│ │ │ │ ├── singleton
│ │ │ │ │ └── Singleton.java
│ │ │ ├── factorymethod
│ │ │ │ └── FactoryMethodExample.java
│ │ │ ├── strategy
│ │ │ │ └── StrategyExample.java
│ │ │ └── spring
│ │ │ ├── singleton
│ │ │ │ ├── SingletonConfig.java
│ │ │ │ └── MySingletonBean.java
│ │ │ ├── factorymethod
│ │ │ │ ├── FactoryMethodConfig.java
│ │ │ │ └── Product.java
│ │ │ └── strategy
│ │ │ ├── StrategyConfig.java
│ │ │ └── StrategyService.java
├── pom.xml
└── README.md
