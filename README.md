# Universe Database

PostgreSQL relational database modeling galaxies, stars, planets, and moons.

Completed as part of the FreeCodeCamp Relational Database certification.

## Files

- `universe.sql` – original dump generated in the FreeCodeCamp Linux environment
- `universe_local.sql` – local-compatible version for Windows and macOS PostgreSQL installs

## Tables

- `galaxy`
- `star`
- `planet`
- `moon`
- `planet_types`

## Setup

This project targets PostgreSQL. Minor syntax adjustments may be required for other database systems.

```bash
psql -U postgres -f universe_local.sql
psql -U postgres -d universe
