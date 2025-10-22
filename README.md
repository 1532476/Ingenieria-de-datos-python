# Ingenieria-de-datos-python
## Recordatorio de comandos git

Aquí tienes una lista de los comandos de Git más comunes y su función:

### Clonar un repositorio
Para obtener una copia de un repositorio remoto existente en tu máquina local.

```bash
git clone <url_del_repositorio>
```

### Ver el estado de tus archivos
Muestra el estado del directorio de trabajo y el área de preparación (staging). Te permite ver qué cambios han sido preparados, cuáles no y qué archivos no están siendo rastreados por Git.

```bash
git status
```

### Preparar cambios (Staging)
Añade cambios del directorio de trabajo al área de preparación para incluirlos en el próximo commit.

```bash
# Añadir un archivo específico
git add <nombre_del_archivo>

# Añadir todos los archivos modificados y nuevos
git add .
```

### Guardar cambios (Commit)
Guarda los cambios preparados (staged) en tu repositorio local. Cada commit tiene un mensaje descriptivo que explica los cambios realizados.

```bashg
git commit -m "Tu mensaje descriptivo aquí"
```

### Enviar cambios al repositorio remoto
Sube el contenido de tu repositorio local (los commits) a un repositorio remoto.

```bash
git push origin <nombre_de_la_rama>
```
*Normalmente, la rama principal se llama `main` o `master`.*

### Actualizar tu repositorio local
Obtiene los últimos cambios del repositorio remoto y los fusiona con tu rama local. Es una combinación de `git fetch` y `git merge`.

```bash
git pull origin <nombre_de_la_rama>
```

### Manejo de ramas
Las ramas te permiten trabajar en diferentes características o versiones de tu proyecto de forma aislada.

```bash
# Listar todas las ramas locales
git branch

# Crear una nueva rama
git branch <nombre_de_la_nueva_rama>

# Cambiar a otra rama
git checkout <nombre_de_la_rama>

# Crear y cambiar a una nueva rama en un solo paso
git checkout -b <nombre_de_la_nueva_rama>
```
