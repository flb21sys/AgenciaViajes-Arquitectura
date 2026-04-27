# 🌍 Agencia de Viajes - Arquitectura de Datos y Despliegue Containerizado

Este repositorio documenta un proyecto integral de gestión de datos, desde el diseño relacional hasta su preparación para despliegue en microservicios.

## 🚀 Infraestructura como Código (Docker)
El proyecto está preparado para ser ejecutado en un entorno inmutable. He configurado un orquestador para que el frontend sea totalmente portable.

**Para levantar el entorno de desarrollo:**
1. Asegúrate de tener Docker instalado.
2. Ejecuta: `docker compose up -d`
3. Accede a la interfaz en: `http://localhost:8080`

## 🏛️ Diseño de Base de Datos (Fase de Ingeniería)
El corazón del proyecto es un backend robusto diseñado bajo estándares profesionales:
* **Normalización:** Estructura normalizada hasta la **3ª Forma Normal (3FN)**.
* **Modelado:** Diagrama Entidad-Relación (E/R) incluido en la documentación.
* **Estado actual:** La lógica de datos se presenta en formato documental (PDF) y físico (Access) para auditoría de diseño.

🎥 **Demostración:** En `/demo` se encuentra el vídeo del sistema funcionando en un entorno LAMP real.

## 📂 Organización
* `/frontend`: Código fuente de la interfaz web (HTML/CSS).
* `/docs`: Documentación técnica y diagramas.
* `/database`: Ficheros de diseño de base de datos.
* `docker-compose.yml`: Configuración de la infraestructura.
