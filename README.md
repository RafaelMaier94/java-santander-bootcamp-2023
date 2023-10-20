# Java Santander Bootcamp 2023
API RESTful criada para o Bootcamp Santander 2023

## Diagrama de classes
``` mermaid
classDiagram
  class User {
    - String name
    - Account account
    - List<Feature> features
    - Card card
    - List<News> news
  }

  class Account {
    - String accountNumber
    - String agency
    - Float balance
    - Float limit
  }

  class Feature {
    - String icon
    - String description
  }

  class Card {
    - String cardNumber
    - Float limit
  }

  class News {
    - String icon
    - String description
  }

  User --> Account
  User --> Feature
  User --> Card
  User --> News
```
