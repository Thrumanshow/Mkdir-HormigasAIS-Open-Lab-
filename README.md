#!/bin/bash

echo "== HormigasAIS Lab: Instalación automática =="

---

# Paso 1: Crear entorno virtual
echo "[1/5] Creando entorno virtual..."
python3 -m venv env

---

# Paso 2: Activar entorno virtual
echo "[2/5] Activando entorno virtual..."
source env/bin/activate

---

# Paso 3: Actualizar pip
echo "[3/5] Actualizando pip..."
pip install --upgrade pip

---

# Paso 4: Instalar el paquete en modo editable
echo "[4/5] Instalando el paquete HormigasAIS Lab..."
pip install -e .

---

# Paso 5: Instalar dependencias adicionales
echo "[5/5] Instalando dependencias..."
pip install -r requirements.txt

echo "== Instalación completada =="
echo "Para empezar a usar el paquete, activa el entorno con:"
echo "    source env/bin/activate"
echo "Y luego puedes importar hormigasais_lab en tus scripts de Python."

---

# Mkdir-HormigasAIS-Open-Lab-
Un espacio donde desarrolladores, diseñadores y creadores puedan colaborar en proyectos de automatización de marketing, scraping de datos, análisis SEO y desarrollo de contenido con IA.

<<https://www.linkedin.com/newsletters/hormigasais-community-7307138608543490048---

---

## 📜 Licencia 

Este proyecto está licenciado bajo [Creative Commons Attribution-ShareAlike 4.0](https://github.com/Thrumanshow/semilla-de-cierre-/blob/main/MIT%20License%20).

