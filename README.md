# gpt-enterprise-hub
Centro neurálgico de un ecosistema empresarial con GPT

# Proyecto MCP - Ecosistema Inteligente con IA, Automatización y Control Empresarial

Este repositorio contiene un sistema completo para integrar un **Módulo de Control Principal (MCP)** con:
- Backend API (Node.js + PostgreSQL)
- Frontend Web (Next.js con login y dashboard)
- Base de datos SQL para autenticación (PhpMyAdmin)
- Automatización de tareas mediante **n8n**
- Comunicación con agentes GPT y conexión a WhatsApp/API externas

---

## Estructura del Proyecto

---

## Tecnologías

- **Node.js** + Express
- **Next.js** + TailwindCSS
- **PostgreSQL** + PhpMyAdmin
- **n8n**
- **OpenAI GPT / API externas**
- **Docker + Docker Compose**

---

## Instalación rápida

1. Clona el proyecto:
```bash
git clone https://github.com/tuusuario/Proyecto-MCP.git
cd Proyecto-MCP

## Copia las variables de entorno:

cp backend-mcp/.env.example backend-mcp/.env
cp frontend-app/.env.local.example frontend-app/.env.local

## Levanta todo con Docker:

bash
Copiar
Editar
docker-compose up -d

## Accede a:

Frontend App: http://localhost:3000

PhpMyAdmin: http://localhost:8080

MCP API: http://localhost:3001

n8n: (configuración aparte o vía webhook)


