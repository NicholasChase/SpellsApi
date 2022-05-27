# Spells Api Spec

## Models
### Character

```
String Name
Class  List<Class>
Int Lvl
Spells List<Spells>
```
### Spell

```
String Name
String Desccription
Class Class
Int Lvl
String resources
String Duration

```
## Endpoints
### Retrieve all spells
GET ` "spell/" `

### Retrieve a spell
GET ` spell/{spell} `

### Retrieve all spells for a class
GET ` "spell/{class}" `

### Retrieve all spells within a level
GET ` "spell/{lvl}" `

### Retrieve all spells within a class and level
GET ` "spell/{class}/{lvl}" `

### Retrieve all spells for a character
GET ` "spell/{character}" `

### Retrieve all spells for a character with in a level
GET ` "spell/{character}/{lvl}" `

### Retrive all spells available for a character with in a level up
GET ` spell/levelUp/{character} `

### Create a Custom Spell
POST ` spell/`

### Update a spell
PUT ` spell/{spell} `

### Create a Character
POST ` character/ `

### Update a characters Spell List
PUT ` character/{spell} `

### Update a Character
PUT ` character/ `
