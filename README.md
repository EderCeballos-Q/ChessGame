
# Python Chess Game

Este proyecto es una implementación de un juego de ajedrez por consola en Python. Permite realizar movimientos válidos, incluyendo el enroque, y al final genera un árbol gráfico con el historial de jugadas.

## integrantes

- **Eder Santiago Ceballos Quiroz**

## Requisitos

- **Python**: versión 3.8 o superior (se recomienda instalar desde [python.org](https://www.python.org/downloads/))
- **Visual Studio Code** con extensión **Python**
- **Graphviz** (programa de escritorio para renderizar gráficos)

## Instalación en Windows

### 1. Instalar Python
- Descárgalo desde: https://www.python.org/downloads/
- Durante la instalación, asegúrate de marcar la opción **"Add Python to PATH"**.

### 2. Instalar Graphviz
- Descárgalo desde: https://graphviz.org/download/
- Instálalo y asegúrate de agregar **la ruta de instalación (por ejemplo, `C:\Program Files\Graphviz\bin`) al PATH** del sistema:
  - Ve a *Panel de control → Sistema → Configuración avanzada del sistema → Variables de entorno*.

### 3. Clonar o descargar el proyecto

Abre VS Code y clona este repositorio, o copia el archivo `chess_game.py` en una nueva carpeta.

### 4. Crear y activar un entorno virtual (opcional pero recomendado)

En la terminal de VS Code:

```bash
python -m venv venv
venv\Scripts\activate
```

### 5. Instalar dependencias

Con el entorno virtual activado, ejecuta:

```bash
pip install anytree graphviz IPython
```

---

## Ejecución del juego

1. Abre el archivo `chess_game.py` en VS Code.
2. Presiona `Ctrl + Shift + P`, selecciona **Python: Select Interpreter** y elige tu entorno virtual.
3. Abre la terminal (`Ctrl + ñ`) y ejecuta:

```bash
python chess_game.py
```

---

## Cómo jugar

- Escribe movimientos en el formato: `e2 e4`, `g1 f3`, etc.
- Para enroque corto: escribe `O-O`
- Para enroque largo: escribe `O-O-O`
- Escribe `exit` para salir del juego

Al finalizar, se generará un archivo `game_tree.png` con el árbol de movimientos.

