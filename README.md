# Facebook marketplace bot publicador y marcador de vendido y agotado

En el archivo profiles.xlsx deben ingresar los datos de su cuenta para que inicie sesion en su cuenta.
En el archivo tabs.xlsx deben colocar los datos  a publicar (en español) al igual que las categorias y todo lo demas (tal cual como esta en facebook) si no, este podria no encontrar el elemento y generar error.

En la carpeta imagenes se colocan las imagenes con el titulo a usar en cada publicacion, este titulo va en el excel junto con su extencion (jpg o la que sea y admita facebook)

# Mac os:

:: Instala Python utilizando Homebrew

```bash
brew install python
```

:: Crea un entorno virtual en la ruta especificada

```bash
python3 -m venv path/to/venv
```

:: Activa el entorno virtual (en macOS/Linux)

```bash
source path/to/venv/bin/activate
```

:: Instala las bibliotecas

```bash
pip3 install -r requirements.txt
```

:: Ejecuta el script con

```bash
python3 app.py
```

# Windows:
:: Instala Chocolatey

```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

:: Instala Python utilizando Chocolatey

```bash
choco install python
```

:: Crea un entorno virtual en la ruta especificada

```bash
python -m venv path\to\venv
```

:: Activa el entorno virtual (en Windows)

```bash
path\to\venv\Scripts\activate
```

:: Instala las bibliotecas

```bash
pip install -r requirements.txt
```

:: Ejecuta el script con

```bash
python app.py
```
