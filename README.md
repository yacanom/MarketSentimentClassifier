# Clasificador de Sentimientos de Titulares Financieros

Este proyecto es un **ejemplo sencillo del uso de [Streamlit](https://docs.streamlit.io/)** para desplegar una aplicación web interactiva basada en un modelo de clasificación de sentimientos aplicado a titulares de noticias del mercado financiero.

## Requisitos previos

Antes de ejecutar esta aplicación, asegúrate de tener instalado lo siguiente:

- [Git](https://git-scm.com/)
- [Git LFS (Large File Storage)](https://git-lfs.com/)
- [Python 3.12](https://www.python.org/)
- [pip](https://pip.pypa.io/)

### Instalación en Linux

```bash
sudo apt update
sudo apt install git git-lfs python3.12 python3-pip -y
```

### Instalación en Windows

1. Descarga e instala:

- [Git for Windows](https://git-scm.com/download/win)
- [Git LFS](https://git-lfs.com/)
- [Python 3.12](https://www.python.org/downloads/windows/)


2. Inicializa Git LFS:

```bash
git lfs install
```

## Recomendación: crear un entorno virtual
    Usa venv o conda para evitar conflictos de dependencias.

Usando venv

```bash
    python3.12 -m venv venv
    source venv/bin/activate  # En Linux/macOS
    venv\Scripts\activate     # En Windows
```

Usando conda
```bash
    conda create -n streamlit-sentiment python=3.12
    conda activate streamlit-sentiment
```

## Instalación de dependencias
    Ejecutar en la carpeta del proyecto
```bash
    pip install -r requirements.txt
```

## Ejecución de la aplicación
```bash
streamlit run app.py
```
Esto abrirá automáticamente el navegador con la aplicación en ejecución. El puerto por defecto que usa streamlit es el 8501

Tambien se puede usar en máquinas linux para dejar corriendo la aplicación para evitar que el proceso se detenga al cerrar la sesión.
```bash
nohup streamlit run app.py &
```