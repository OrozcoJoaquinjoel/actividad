# Menú Dinámico con Flask, Jinja2 y Bootstrap

**Autor:** Joel Orozco

## Descripción
Este proyecto es una aplicación web sencilla desarrollada con Flask. Muestra un menú de navegación dinámico y responsivo, generado a partir de un diccionario anidado en Python y renderizado recursivamente en la plantilla HTML usando Jinja2. El diseño y la responsividad se logran con Bootstrap.

## Estructura de archivos
- `main.py`: Archivo principal de la aplicación Flask.
- `templates/menu.html`: Plantilla HTML con el menú dinámico.
- `README.md`: Este archivo.

## Requisitos
- Python 3.x
- Flask

## Instalación y ejecución
1. (Opcional) Crea y activa un entorno virtual:
   ```
   python -m venv venv
   venv\Scripts\activate  # En Windows
   # o
   source venv/bin/activate  # En Linux/Mac
   ```
2. Instala Flask:
   ```
   pip install flask
   ```
3. Ejecuta la aplicación:
   ```
   python main.py
   ```
4. Abre tu navegador y visita: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

## Notas
- El menú es completamente dinámico y soporta cualquier cantidad de subniveles.
- El diseño es responsivo gracias a Bootstrap (CDN).
