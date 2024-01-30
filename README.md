Prisma Accelerate engine running on Deno Deploy.

## Get Started

Create API key.
```bash
npx prisma-accelerate-local -s SECRET -m postgres://USER:PASSWORD@HOST:PORT/DBNAME?schema=public

# exapmle output
eyJhbGciOiJIUzI1NiJ9.eyJkYXRhc291cmNlVXJsIjoicG9zdGdyZXM6Ly9VU0VSOlBBU1NXT1JEQEhPU1Q6UE9SVC9EQk5BTUU_c2NoZW1hPXB1YmxpYyIsImlhdCI6MTcwNjYzMDQzNCwiaXNzIjoicHJpc21hLWFjY2VsZXJhdGUifQ.6o1FPOs-YVNRIWbkY3K1vvTvFupXn25qlkDGJnXUEWo
```

Set database url in client-side env file.
```bash
# .env.example
DATABASE_URL = "prisma://DENO_DOMAIN/?api_key=eyJhbGciOiJIUzI1NiJ9.eyJkYXRhc291cmNlVXJsIjoicG9zdGdyZXM6Ly9VU0VSOlBBU1NXT1JEQEhPU1Q6UE9SVC9EQk5BTUU_c2NoZW1hPXB1YmxpYyIsImlhdCI6MTcwNjYzMDQzNCwiaXNzIjoicHJpc21hLWFjY2VsZXJhdGUifQ.6o1FPOs-YVNRIWbkY3K1vvTvFupXn25qlkDGJnXUEWo"
```

## Credit
 - [Original Repository](https://github.com/SoraKumo001/prisma-accelerate-deno) (@SoraKumo001)

## Documentation
 - [Deno Deploy](https://docs.deno.com/deploy/manual)
 - [Prisma](https://www.prisma.io/docs)