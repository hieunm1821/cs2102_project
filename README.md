## CS2102 Database System - AY2122 Sem 1

### Project of Team 70

### Setting up Database

Run the following commands to set up the database correctly:

```
psql -U <username>
CREATE DATABASE cs2102_project;
\c cs2102_project
\i schema.sql
\i data.sql
\i proc.sql
```

Note: File location are relative, so ensure you are at the right location. All files required are located inside
`Team70` folder.