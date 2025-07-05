# 🐾 VETTsafe – Sistema de Gestión Veterinaria

## 📝 Descripción del Proyecto

**VETTsafe** es una aplicación desarrollada en Python para la gestión eficiente de información de mascotas y sus consultas médicas en clínicas veterinarias. Permite registrar, editar y listar datos de clientes y mascotas mediante operaciones CRUD, facilitando la organización interna y el acceso rápido a los registros.

> Este proyecto está disponible bajo la [Licencia MIT](https://github.com/francisxo999/Proyecto-Semestral/blob/main/LICENSE).

---

## ⚙️ Tecnologías Utilizadas

- ![Python](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg) **Python** – Lógica y operaciones CRUD  
- ![SQLite](https://upload.wikimedia.org/wikipedia/commons/3/38/SQLite370.svg) **SQLite** – Base de datos local  
- ![VSCode](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg) **Visual Studio Code** – Entorno de desarrollo  
- ![Figma](https://upload.wikimedia.org/wikipedia/commons/3/33/Figma-logo.svg) **Figma** – Diseño de interfaz  
- ![Excel](https://upload.wikimedia.org/wikipedia/commons/3/34/Microsoft_Office_Excel_%282019%E2%80%93present%29.svg) **Excel** – Carta Gantt  
- ![Jira](https://upload.wikimedia.org/wikipedia/commons/8/8a/Jira_Logo.svg) **Jira** – Gestión ágil del proyecto

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/francisxo999/Proyecto-Semestral.git
   ```
2. Abre la carpeta en Visual Studio Code.
3. Crea y activa un entorno virtual:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate  # Windows
   ```
4. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
5. Ejecuta la aplicación:
   ```bash
   python main.py
   ```

> Asegúrate de tener Python 3.11 o superior instalado.

---

## 📦 Requisitos del Proyecto (`requirements.txt`)

```
certifi==2025.6.15
charset-normalizer==3.4.2
holidays==0.75
idna==3.10
pip==25.1.1
PySide6==6.9.1
PySide6-Addons==6.9.1
PySide6-Essentials==6.9.1
python-dateutil==2.9.0.post0
requests==2.32.4
shiboken6==6.9.1
six==1.17.0
urllib3==2.5.0
```

---

## 🎨 Diseño de Interfaz

- Prototipo Figma: [Ver diseño](https://www.figma.com/proto/dW6zv0OQ8aZEJCwbGtbomC/Vettsafe?node-id=15-115&starting-point-node-id=15%3A115)

**Diferencias clave con el prototipo:**
- Funcionalidades CRUD completamente operativas
- Base de datos funcional y persistencia asegurada
- Simplificación de algunas vistas para mayor fluidez en el flujo

---

## 📅 Gestión y Planificación

- **Jira (Scrum + backlog):**  
  [Tablero del proyecto](https://vettsafe.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog)

- **Carta Gantt:**  
  [Planificación temporal](https://docs.google.com/spreadsheets/d/1c3QkWdsqGV5yM9EpvRcGAK7bTbtyMJmF/edit?usp=sharing)

---

## 📚 Metodología de Desarrollo

Se utilizó **Scrum** como marco ágil, con sprints semanales, planificación por historias de usuario, seguimiento mediante Jira, y revisión continua del prototipo. La Carta Gantt sirvió como apoyo visual y guía para las etapas de trabajo.

---

## 👥 Equipo de Desarrollo

| Nombre             | Rol                                                                  |
|--------------------|-----------------------------------------------------------------------|
| **Francisco Vera** | Líder de equipo, desarrollo backend y base de datos                  |
| **Javier Cataldo** | Apoyo en base de datos y planificación con metodología Scrum         |
| **Cristóbal González** | Gestión de tareas en Jira y control de la Carta Gantt           |

---

## 📈 Resumen Semanal de Avances

| Semana | Avances clave |
|--------|---------------|
| 1      | Idea definida, repositorio y licencia creados |
| 2      | Estructura inicial en Python y modelo de base de datos |
| 3      | Mejoras en interfaz tras retroalimentación |
| 4      | Organización de carpetas y entorno |
| 5      | Programación inicial en VSCode, conexión DB |
| 6      | Implementación de ramas, creación de Jira y Gantt |
| 7      | Organización del repositorio, documentación inicial |
| 8      | Desarrollo de entidades `Cliente` y `Mascota` con CRUD |
| 9      | Revisión del docente y ajustes según feedback |
| 10     | Reorganización del repositorio, nuevas tareas asignadas |
| 11     | Actualización de Carta Gantt, investigación sobre APIs |

> Actualmente nos encontramos en la **fase final**, enfocándonos en pruebas y mejoras antes de la entrega.

---

## 📂 Vinculación con Otras Asignaturas

- **Base de Datos**
- **Ingeniería de Software**
- **Desarrollo Fullstack**
- **Fundamentos de Programación**

---

## 🧩 Próximos Pasos (posdesarrollo)

- Integración con APIs externas (ej. datos de vacunas o razas)
- Mejora de interfaz gráfica (PySide6 o Tkinter)
- Generación de reportes en PDF o Excel

---

¡Gracias por visitar el repositorio!  
Cualquier sugerencia o aporte es bienvenido en la sección de issues o pull requests.
