# BDG

## Pré-requisitos

### 1. Crie o banco de dados

```bash
createdb BDG
```

### 2. Ative o PostGIS

```bash
psql -d BDG -c "CREATE EXTENSION postgis;"
```

### 3. Restaure o arquivo

**Linux / Mac:**

```bash
gunzip -c db.sql.gz | psql -d BDG
```
