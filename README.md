# Product Microservice

## Dev

1. Clonar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` en la raíz del proyecto basado en el archivo `.env.template`:
4. Ejecutar migración de prisma `npx prisma migrate dev`
5. Levantar el servidor de NATS

```bash
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```

6. Ejecutar el proyecto `npm run start:dev`
