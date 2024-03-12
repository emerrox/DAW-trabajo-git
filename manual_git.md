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
