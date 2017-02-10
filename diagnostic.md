# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
It defines/creates the framework of the app
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
Model layer
```

Which layer in the MVC pattern communicates with the model?

```md
Controller layer
```

Why don't we use views in our interpretation of the MVC pattern?

```md
Not sure what is being asked here. Please advise!
```

What does C.R.U.D stand for?

```md
Create, Retrieve, Update, Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
Controller and View
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
Create_table
drop_table
add_column
remove_column
rename_column
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
1. client sends request to server
2. server sends request to controller
3. controller looks at request and makes it into JSON
4. controller sends JSON request to Model
5. Model goes into database and see if it can fulfill the request
6. Model sends response back to controller
7. Controller sends response back to server
8. Server sends response back to client
```

What is the command to generate a new rails-api app?

```bash
rails new
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
db:drop
db:create
db:migrate
db:seed
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails generate scaffold pet
```
