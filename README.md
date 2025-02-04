# 👨‍🎓 Java orientado a Objetos e API

👾Repositório destinado para armazenar meus estudos e projetos desenvolvidos no curso de Java orientado a objetos e API restful da DIO no bootcamp da Santander, onde aprimorei meus conhecimentos de Orientação a Objetos e fui introduzido aos mundos das APIS.


### 📚 Tecnologias

![Java](https://img.shields.io/badge/Java-D65DB1?style=for-the-badge&logo=openjdk&logoColor=white) 



# Santander-dev-bootcamp-2024

## Diagrama de classes

```mermaid
classDiagram
  class User {
    -String name
    -Account account
    -Feature[] features
    -Card card
    -News[] news
  }

  class Account {
    -String number
    -String agency
    -Number balance
    -Number limit
  }

  class Feature {
    -String icon
    -String description
  }

  class Card {
    -String number
    -Number limit
  }

  class News {
    -String icon
    -String description
  }

  User "1" *-- "1" Account
  User "1" *-- "N" Feature
  User "1" *-- "1" Card
  User "1" *-- "N" News
```
