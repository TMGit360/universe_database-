# Universe Database

A PostgreSQL relational database modeling galaxies, stars, planets, and moons. Created as part of FreeCodeCamp’s Relational Database certification.

## Files
- `universe.sql` – PostgreSQL dump containing database schema, constraints, and sample data

## Technologies
- PostgreSQL
- SQL

## Database structure
The database includes the following tables:

- `galaxy`
- `star`
- `planet`
- `moon`
- `planet_types`

## Relationships
- Each galaxy can have multiple stars
- Each star belongs to a galaxy and can have multiple planets
- Each planet belongs to a star and can have multiple moons
- `planet_types` stores descriptive information for planets

Primary keys and foreign keys are used to enforce relationships between tables.

## Setup
To load the database from the SQL dump:

```bash
psql -U freecodecamp -f universe.sql
