# Porjeto dio api rest
Java Restful api 

## Diagrama de classes

```mermaid
classDiagram
  class User {
    - String name
    - Account account
    - Feature[] features
    - Card card
    - News[] news
  }
  
  class Account {
    - String number
    - String agency
    - float balance
    - float limit
  }
  
  class Feature {
    - String icon
    - String description
  }
  
  class Card {
    - String number
    - float limit
  }
  
  class News {
    - String icons
    - String description
  }
  
  User --> Account
  User --> Feature
  User --> Card
  User --> News
```
