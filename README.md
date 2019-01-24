# MongoDB

A compilation of the most common commands.

## Log into the system

Log into the system and select a database (optional):
```bash
mongo [dbname]
```

Log into the system with a specific user and select a database (optional):
```bash
mongo [dbname] -u <user> -p
```

## Display commands

Once logged into the system we can use the following common commands:

```bash
# display databases
show dbs

# use a specific database
use photomanager

# display collections
show collections
```

## Users

```JavaScript
// Creates a database user with read and write permissions.
db.createUser({
  user: 'username',
  pwd: 'password',
  roles: ['readWrite']
});

// drop a specific database user
db.dropUser('username');
```
