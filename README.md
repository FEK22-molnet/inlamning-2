# CRUD med DynamoDb, Lambda och AWS Gateway

Individuell inlämning

Du ska skapa en enkel CRUD med hjälp av DynamoDb, Lambda och AWS Gateway. Du får själv välja vad som skall sparas in i DynamoDb. Det kan vara badleksaker, kattungar, traktormärken eller något annat skoj som tilltalar dig.

### G-kriterier:
* Skapa en DynamoDb-tabell
* Skapa en Lambda-funktion
* Lägg på permissions på DynamoDb-tabellen
* Skapa en separat funktion i Lambda för 'Create'-delen i CRUD
* Skapa en separat funktion i Lambda för 'Read'-delen i CRUD
* Skapa en separat funktion i Lambda för 'Update'-delen i CRUD
* Skapa en separat funktion i Lambda för 'Delete'-delen i CRUD
* Sätt upp API Gateway
* Definiera dina API routes (ex: '/items', '/items/{id}'} som korresponderar med dina CRUD-operationer.
* Länka dina endponts med dina Lambda-funktioner
* Deploya ditt API
* Testa ditt API i Insomnia eller Postman

### VG
* Lägg till authorization på ditt API, valfritt i hur du gör det

Level-up:
* Skapa en stilig frontend
