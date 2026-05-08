# 🚀 Actividad-n8n

Proyecto de automatización de flujos de trabajo utilizando **n8n**, una plataforma open-source de automatización low-code que permite conectar aplicaciones, APIs y servicios mediante workflows visuales.

---

# 📌 Descripción

Este repositorio contiene actividades y ejemplos desarrollados en **n8n**, enfocados en la automatización de procesos, integración de APIs y creación de flujos de trabajo personalizados.

n8n permite construir automatizaciones mediante nodos visuales y lógica personalizada usando JavaScript o integraciones externas.

## 🎯 Objetivos del Proyecto

- Automatizar tareas repetitivas
- Integrar servicios y APIs
- Aprender el funcionamiento de n8n
- Implementar workflows reutilizables
- Gestionar procesos mediante automatización visual

---

# 🛠 Tecnologías Utilizadas

- **n8n**
- **Node.js**
- **Docker** (opcional)
- **JSON Workflows**
- **REST APIs**
- **JavaScript**

---

# 📂 Estructura del Proyecto

```bash
Actividad-n8n/
│
├── workflows/              # Workflows exportados desde n8n
├── assets/                 # Recursos visuales e imágenes
├── docs/                   # Documentación adicional
├── docker-compose.yml      # Configuración Docker
└── README.md
```

---

# ⚙️ Requisitos

Antes de ejecutar el proyecto asegúrate de tener instalado:

- Node.js >= 18
- npm o pnpm
- Docker (opcional)
- n8n

---

# 🚀 Instalación

## 🔹 Instalación Local

Instalar n8n globalmente:

```bash
npm install n8n -g
```

Ejecutar n8n:

```bash
n8n
```

Abrir en el navegador:

```bash
http://localhost:5678
```

---

## 🔹 Instalación con Docker

Crear volumen:

```bash
docker volume create n8n_data
```

Ejecutar contenedor:

```bash
docker run -it --rm \
 --name n8n \
 -p 5678:5678 \
 -v n8n_data:/home/node/.n8n \
 docker.n8n.io/n8nio/n8n
```

---

# 📥 Importar Workflows

1. Abrir n8n
2. Ir a **Workflows**
3. Seleccionar:
   - **Import from File**
4. Elegir el archivo `.json`

---

# 🧠 Características

✅ Automatización visual  
✅ Integración con APIs  
✅ Workflows reutilizables  
✅ Compatible con IA  
✅ Low-Code / No-Code  
✅ Escalable  
✅ Open Source  
✅ Compatible con Docker  

---

# 📌 Casos de Uso

- Automatización de correos
- Integración con GitHub
- Bots de Telegram
- Integración con OpenAI
- Procesamiento de datos
- ETL y pipelines
- Automatización empresarial

---

# 📸 Capturas del Proyecto

Agrega aquí imágenes de los workflows.

```bash
/assets/workflow-example.png
```

---

# 🔒 Seguridad

## Recomendaciones

- No subir credenciales al repositorio
- Utilizar variables de entorno
- Configurar autenticación
- Mantener n8n actualizado
- Realizar backups periódicos

---

# 🌐 Recursos Oficiales

## n8n

- Documentación: https://docs.n8n.io/
- GitHub: https://github.com/n8n-io/n8n
- Docker Hub: https://hub.docker.com/r/n8nio/n8n

---

# 📈 Ventajas de n8n

- Open Source
- Self-hosted
- Más de 400 integraciones
- Compatible con IA
- Automatización visual
- Fácil de extender
- Integración con APIs REST

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas.

## Pasos

1. Hacer fork del proyecto
2. Crear nueva rama:

```bash
git checkout -b feature/nueva-funcionalidad
```

3. Realizar commit:

```bash
git commit -m "Nueva funcionalidad"
```

4. Subir cambios:

```bash
git push origin feature/nueva-funcionalidad
```

5. Abrir Pull Request

---

# 👨‍💻 Autor

Desarrollado por:

## JP-hub-coder

GitHub:
https://github.com/JP-hub-coder

---

# ⭐ Recomendaciones

- Utilizar Docker para producción
- Versionar workflows en GitHub
- Utilizar variables de entorno
- Separar workflows por módulos
- Documentar cada automatización

---

# 📚 Referencias

n8n es una plataforma de automatización open-source enfocada en workflows visuales y automatización empresarial.

Permite conectar servicios mediante nodos reutilizables y lógica personalizada usando JavaScript y APIs externas.

---
