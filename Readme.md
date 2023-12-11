## Registro de Actividades con Git

A continuación, se presenta un registro de las acciones realizadas con Git en el proyecto:

### 1. Activación del Entorno Virtual de Python (venv)

```bash
& c:/Users/wwwed/OneDrive/Escritorio/Soft/venv/bin/Activate.ps1
```

Este comando activa el entorno virtual de Python (venv) en la carpeta del proyecto.

### 2. Navegación a la Carpeta del Entorno Virtual

```bash
cd .\venv\
```

Se cambia al directorio `venv` dentro del proyecto.

### 3. Navegación a la Carpeta `bin` dentro del Entorno Virtual

```bash
cd .\bin\
```

Se navega a la carpeta `bin` dentro del entorno virtual.

### 4. Desactivación del Entorno Virtual

```bash
deactivate
```

Desactiva el entorno virtual de Python.

### 5. Regreso a la Carpeta Anterior

```bash
cd  ..
```

Regresa a la carpeta anterior.

### 6. Regreso a la Carpeta Principal del Proyecto

```bash
cd ..
```

Regresa a la carpeta principal del proyecto.

### 7. Inicialización de un Repositorio Git

```bash
git init
```

Crea un nuevo repositorio Git en la carpeta del proyecto.

### 8. Verificación del Estado del Repositorio

```bash
git status
```

Verifica el estado del repositorio. En este caso, muestra archivos no rastreados: `.gitignore` y `requirements.txt`.

### 9. Adición de Archivos al Área de Preparación

```bash
git add *
```

Agrega todos los archivos al área de preparación.

### 10. Verificación del Estado del Repositorio después de la Adición

```bash
git status
```

Muestra que los archivos `.gitignore` y `requirements.txt` están listos para ser confirmados.

### 11. Realización del Primer Commit

```bash
git commit -m "First Commit"
```

Crea el primer commit con el mensaje "First Commit".

### 12. Verificación del Estado del Repositorio después del Commit

```bash
git status
```

Indica que no hay cambios pendientes y el directorio de trabajo está limpio.

### 13. Visualización del Registro de Commits

```bash
git log
```

Muestra el historial de commits, incluido el commit inicial.

### 14. Visualización del Registro de Commits con Gráficos

```bash
git log --graph
```

Muestra el historial de commits en formato gráfico.

---