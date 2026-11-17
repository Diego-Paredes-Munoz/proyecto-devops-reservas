
# Sistema de Reservas Médicas - DevOps

Proyecto académico de la Unidad 1 de DevOps.

## Objetivo
Simular una plataforma web de reserva de horas médicas
utilizando HTML, CSS, Nginx y Docker.

## Requisitos
- Docker Desktop
- Docker Compose
- Git

## Ejecución
docker compose up -d --build

## Verificación
Abrir http://localhost:8080

Consultar estado:
docker compose ps

Consultar logs:
docker compose logs

Consultar métricas:
docker stats --no-stream

## Detener
docker compose down

## Seguridad
El repositorio no contiene credenciales ni datos reales.
El formulario es demostrativo y no registra reservas.
El archivo .env está excluido del repositorio mediante
.gitignore.
