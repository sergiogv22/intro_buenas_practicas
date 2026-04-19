# 📊 Curso de Introducción a la Ciencia de Datos con Python

Este repositorio contiene ejercicios, ejemplos y buenas prácticas para un curso de introducción a la ciencia de datos utilizando Python.

---

## ⚙️ Preparación del entorno de trabajo

Para trabajar con este repositorio, es recomendable crear un entorno virtual de Python para aislar las dependencias del proyecto.

### 🔹 1. Crear un entorno virtual

#### 🪟 Windows (PowerShell)

```powershell
python -m venv venv
```

Activar el entorno:

```powershell
.\venv\Scripts\Activate.ps1
```

---

#### 🐧 Linux

```bash
python3 -m venv venv
```

Activar el entorno:

```bash
source venv/bin/activate
```

---

#### 🍎 macOS

```bash
python3 -m venv venv
```

Activar el entorno:

```bash
source venv/bin/activate
```

---

### 🔹 2. Instalar dependencias

Una vez activado el entorno virtual, instala las dependencias del proyecto usando el archivo `requirements.txt`.

#### 🪟 Windows (PowerShell)

```powershell
pip install -r requirements.txt
```

---

#### 🐧 Linux / 🍎 macOS

```bash
pip install -r requirements.txt
```

---

## ✅ Notas

* Asegúrate de tener Python 3.8 o superior instalado.
* Si el comando `python` no funciona en tu sistema, prueba con `python3`.
* Para salir del entorno virtual, ejecuta:

```bash
deactivate
```

* En el archivo .gitignore incluímos el venv para no subir odo el volumen de dependencias de pyhon al repo.

## Trabajo en Notebooks

* Activa tu entorno virtual. Luego, instala el paquete ipykernel (incluído en requirements.txt)

``` bash
pip install ipykernel
```

### macOS / Linux

``` bash
python -m ipykernel install --user --name IntroDS --display-name "Python (IntroDS)"
```

### Windows (PowerShell)

``` powershell
python -m ipykernel install --user --name IntroDS --display-name "Python (IntroDS)"
```