# Cassandra

Database schema and migrations for Cassandra. Contains:
- SQL scripts
- ORM models
- Seed data
- Query examples

## Setup

```sql
psql -f migrations/001_init.sql
```

## Migrations

Run migrations with:
```bash
npm run migrate
```
