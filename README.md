## Log into the system

Log into the system and select a database (optional):
> mongo [dbname]

Log into the system with a specific user and select a database (optional):
> mongo [dbname] -u <user> -p

## Common commands

Once logged into the system we can use the following common commands:

```{r, engine='bash', count_lines}
// display a list of available databases
show dbs

// use a specific database
use photomanager
show collections
```

