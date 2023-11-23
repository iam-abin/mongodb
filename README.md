after mongodb installation and setup,

open terminal,

### to enter into mongodb shell

 type,

``` mongosh ```

- to exit mongo shell type,

```exit```

- to see databases names

```show dbs```

- to use a database or create a new database,

```use database_name```

- to see all the collections in this db,

```show collections```

- to create a collection

```db.createCollection("collection_name")```

- we can also create a new collection while insertion a data,

eg:-

```db.users.insertOne(add_data)```

- to insert data from the given file 

1. open insertMany function

 ````db.users.insertMany(```

 2. copy and paste the above file contents 

 3. close this function

 ```)```


