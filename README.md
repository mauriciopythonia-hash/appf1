# AppF1

Dashboard web interactivo de Fórmula 1 (temporadas 2018-2025), construido en Python con Streamlit, pandas y Plotly.

> 🚧 Proyecto en construcción. Se desarrolla paso a paso como material para un curso de Python.

## Requisitos

- Python 3.14
- Git

## Instalación

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/mauriciopythonia-hash/appf1.git
   cd appf1
   ```

2. Crear y activar el entorno virtual:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate      # macOS / Linux
   .venv\Scripts\activate         # Windows
   ```

3. Instalar las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

### Nota para macOS

Si Python se instaló desde python.org y aparece el error `CERTIFICATE_VERIFY_FAILED`, ejecutar una vez:

```bash
open "/Applications/Python 3.14/Install Certificates.command"
```