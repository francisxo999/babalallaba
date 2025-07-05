# 🐾 VETTsafe – Sistema de Gestión Veterinaria

## 📝 Descripción del Proyecto

**VETTsafe** es una aplicación desarrollada en Python para la gestión eficiente de información de mascotas y sus consultas médicas en clínicas veterinarias. Permite registrar, editar y listar datos de clientes y mascotas mediante operaciones CRUD, facilitando la organización interna y el acceso rápido a los registros.

> Este proyecto está disponible bajo la [Licencia MIT](https://github.com/francisxo999/Proyecto-Semestral/blob/main/LICENSE).
> 
---

## ⚙️ Tecnologías Utilizadas

- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="22"/>  **Python:** Lenguaje utilizado para la programación de la lógica del sistema y las operaciones CRUD.
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="Visual Studio Code" width="20"/> **Visual Studio Code:** Editor de código fuente empleado para programar y organizar los archivos del sistema.
- <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/SQLite370.svg" alt="SQLite" width="38"/> **SQLite:** Motor de base de datos utilizado para almacenar los registros de manera local y eficiente.
- <img src="https://upload.wikimedia.org/wikipedia/commons/3/33/Figma-logo.svg" alt="Figma" width="15"/>  **Figma:** Plataforma empleada para diseñar las interfaces de usuario y mejorar la experiencia visual.
- <img src="https://upload.wikimedia.org/wikipedia/commons/3/34/Microsoft_Office_Excel_%282019%E2%80%93present%29.svg" alt="Excel" width="20"/> **Excel:** Usado para desarrollar y organizar la Carta Gantt del proyecto.  
- <img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Jira_Logo.svg" alt="Jira" width="38"/> **Jira:** Herramienta de gestión de proyectos utilizada para organizar las tareas del equipo.

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
python-dateutil==2.9.0.post0
requests==2.32.4
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

- **Semana 1:**  
  Se definió la idea del sistema, se creó la licencia del proyecto y se planificaron las tareas iniciales.

- **Semana 2:**  
  Se desarrolló la estructura base en Python y el prototipo de la base de datos. También se diseñaron las primeras interfaces de usuario.

- **Semana 3:**  
  Se mejoraron las interfaces con base en la retroalimentación recibida, reorganizando las pantallas y optimizando la experiencia del usuario.

- **Semana 4:**  
  Se revisaron los avances gráficos y se organizó el entorno de trabajo, reestructurando carpetas y archivos.

- **Semana 5:**  
  Se inició la programación en Visual Studio Code, se configuraron las extensiones necesarias y se comenzó la implementación de la base de datos.

- **Semana 6:**  
  Se implementaron ramas en GitHub para permitir el trabajo independiente del equipo. Además, se creó un tablero en [Jira](https://vettsafe.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog?atlOrigin=eyJpIjoiNjFhMWQzOTVmZDQ3NDUxYTlkZjlkMmRlMjdkMWU4ZWIiLCJwIjoiaiJ9) y una [Carta Gantt](https://docs.google.com/spreadsheets/d/1c3QkWdsqGV5yM9EpvRcGAK7bTbtyMJmF/edit?usp=sharing&ouid=117040996252373578955&rtpof=true&sd=true) para la planificación del proyecto.

- **Semana 7:**  
  Se organizaron y actualizaron los archivos del repositorio, incluyendo capturas y documentos relacionados con la base de datos, Jira y la Carta Gantt, con el fin de mejorar la claridad y el seguimiento del proyecto.

- **Semana 8:**  
  Se avanzó en el desarrollo de la base de datos en SQL y el código en Visual Studio Code, logrando la conexión entre ambos e implementando las primeras dos entidades: CLIENTE y MASCOTA, permitiendo agregar datos de forma sencilla y efectiva.

- **Semana 9:**  
  Recibimos retroalimentación del profesor sobre los avances, tanto en el repositorio como en el tablero de Jira y el código de Python conectado con la base de datos. Nos entregó recomendaciones y destacó los aspectos positivos del trabajo realizado hasta el momento.

- **Semana 10:**  
  Se reorganizaron las carpetas del repositorio para mantener un orden lógico y facilitar la navegación entre semanas. Además, se agregaron nuevas tareas en el tablero de Jira, asignando responsabilidades específicas a cada integrante del equipo.

- **Semana 11:**  
  Se actualizó la Carta Gantt incluyendo nuevos sprints a partir del sprint 3. Se añadieron nuevas tareas en Jira, asignándolas a los integrantes del equipo. En el archivo README se incorporaron los enlaces a Jira y Figma en la sección de metodología de desarrollo. También se realizó una investigación sobre APIs para evaluar su posible integración en el sistema.

- **Semana 12:**
   Se realizaron cambios importantes en la base de datos para mejorar su estructura y rendimiento. También se ajustaron elementos de la interfaz para hacerla más intuitiva. Además, se integró la API pública [Nager.Date](https://date.nager.at/) para obtener información sobre feriados, lo que permitió explorar nuevas funcionalidades en el sistema.

*Actualmente nos encontramos en la fase final de desarrollo, enfocados en pruebas y mejoras antes de la entrega final.*

---

## 📂 Vinculación con Otras Asignaturas

- **Base de Datos**
- **Ingeniería de Software**
- **Desarrollo Fullstack**
- **Fundamentos de Programación**
