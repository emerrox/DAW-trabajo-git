# GIT

## ¿Qué es GIT?
- Un sistema de control de versiones distribuido, rápido y escalable que ayuda a crear el código con diferentes versiones y un historial de cambios

### Ventajas de usar Git

- **Control de Versiones:**
  - Permite rastrear cambios en el código y revertir a versiones anteriores si es necesario.

- **Colaboración:**
  - Facilita el trabajo colaborativo permitiendo a múltiples desarrolladores trabajar en el mismo proyecto.

- **Ramas (Branches):**
  - Posibilidad de trabajar en ramas independientes para desarrollar nuevas características sin afectar la rama principal.

- **Distribuido:**
  - Cada desarrollador tiene una copia completa del repositorio, lo que facilita el trabajo sin conexión.

- **Historial Detallado:**
  - Proporciona un historial detallado de cambios, quién los realizó y cuándo.

## Comandos Básicos de Git

1. **git init:**
   - Inicia un nuevo repositorio Git en el directorio actual.

2. **git clone [URL]:**
   - Clona un repositorio remoto en tu máquina local.

3. **git add [archivo(s)]:**
   - Agrega cambios al área de preparación (staging) para ser incluidos en el próximo commit.

4. **git commit -m "mensaje":**
   - Crea un nuevo commit con los cambios en el área de preparación y añade un mensaje descriptivo.

5. **git status:**
   - Muestra el estado actual del repositorio, incluyendo archivos sin seguimiento, modificados y en el área de preparación.

6. **git log:**
   - Muestra un historial de commits con información detallada.

7. **git pull:**
   - Obtiene cambios desde un repositorio remoto y los fusiona con la rama actual.

8. **git push:**
   - Envía commits locales a un repositorio remoto.

9. **git branch:**
   - Muestra una lista de ramas y resalta la rama actual.

10. **git branch [nombre_rama]:**
    - Crea una nueva rama.

11. **git checkout [nombre_rama]:**
    - Cambia a la rama especificada.

12. **git merge [nombre_rama]:**
    - Fusiona la rama especificada con la rama actual.

13. **git remote -v:**
    - Muestra las URLs de los repositorios remotos configurados.

14. **git fetch:**
    - Descarga cambios desde un repositorio remoto, pero no los fusiona con tu rama actual.

15. **git diff:**
    - Muestra las diferencias entre los cambios sin preparar y la última versión guardada.

## Tipos de Usuarios en Git

En Git, hay varios tipos de usuarios que interactúan con un repositorio. Estos roles definen los niveles de acceso y las responsabilidades que cada usuario tiene en el proyecto.

### 1. Usuario Anónimo:
- **Descripción:** Accede al repositorio sin autenticación.
- **Acciones Típicas:** Solo puede realizar operaciones de lectura (clonar).

### 2. Colaborador:
- **Descripción:** Miembro del equipo que contribuye al desarrollo del proyecto.
- **Acciones Típicas:** Clonar, confirmar cambios, enviar solicitudes de extracción.

### 3. Propietario del Repositorio:
- **Descripción:** Persona o equipo que posee el repositorio.
- **Acciones Típicas:** Configuración del repositorio, gestión de acceso, fusionar cambios.

### 4. Revisor:
- **Descripción:** Responsable de revisar y aprobar cambios propuestos.
- **Acciones Típicas:** Revisar código, aprobar o rechazar solicitudes de extracción.

### 5. Lector:
- **Descripción:** Usuario con permisos solo de lectura.
- **Acciones Típicas:** Clonar y leer el repositorio, pero no puede realizar cambios.

### 6. Contribuidor Externo:
- **Descripción:** Persona externa que realiza contribuciones ocasionales.
- **Acciones Típicas:** Enviar cambios propuestos a través de solicitudes de extracción.

### 7. Administrador del Sistema:
- **Descripción:** Persona encargada de la administración del sistema que aloja el repositorio.
- **Acciones Típicas:** Configuración del servidor Git, gestión de usuarios y permisos.

### 8. Usuario de Solo Lectura:
- **Descripción:** Tiene permisos solo de lectura en el repositorio.
- **Acciones Típicas:** Clonar y leer el repositorio, pero no puede realizar cambios.

### 9. Desarrollador Principal:
- **Descripción:** Miembro clave del equipo, a menudo responsable de la toma de decisiones importantes.
- **Acciones Típicas:** Fusionar cambios críticos, liderar el desarrollo.
