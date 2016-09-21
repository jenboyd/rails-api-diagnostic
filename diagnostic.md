# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
The backend and store and transfer data.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The controller communicates with the model to retrieve data.
```

Which layer in the MVC pattern communicates with the model?

```bash
The controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
We do not use views because we are creating our own front end with other languages.
```

What does C.R.U.D stand for?

```bash
Create, Read, Update, Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
The Router
```

List at least 5 standard actions that C.R.U.D corresponds to?

```bash
POST, PATCH, GET, DELETE
```

A user action fires a `GET` request for `/persons/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
 - The client communicates this request to the server
 - The server communicates this as a Read request to the controller
 - The controller recieves this request and send it to the model
 - The model communicates with the database to get the requested information.
 - This information is sent mack to the model
 - The model sends the information back to the controller
 - The controller returns it to the server, which returns it to the client.
 - The client displays the users request to the user.
```

What is the command to generate a new rails-api app?

```bash
Rails generate
```

What is the command to start an instance of a rails server?

```bash
bunde exec rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
- DROP db
- CREATE db
- db:migrate


```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
ALTER TABLE pets
  ADD COLUMN name TEXT,
  ADD COLUMN age INTEGER
```
