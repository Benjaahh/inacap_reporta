# INACAP Reporta

Aplicación web desarrollada con Django y MySQL que permite a estudiantes y encargados reportar y gestionar incidencias de infraestructura en el campus INACAP.[file:76]

## Características

- Registro e inicio de sesión de usuarios.
- Roles: Estudiante y Encargado, con paneles diferenciados (usuario y administración).[file:76]
- CRUD completo de incidencias: título, descripción, categoría, ubicación, urgencia, estado y foto opcional.[file:76]
- Listados de incidencias con filtros básicos y cambio de estado por parte de los encargados.[file:76]

## Requisitos

- Python 3.x  
- MySQL / MariaDB  
- pip y virtualenv

## Instalación rápida

git clone <URL_DEL_REPO>
cd inacap-reporta
python -m venv venv
venv\Scripts\activate # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

text

Abrir en el navegador: `http://127.0.0.1:8000/`.[file:76]

## Uso básico

1. Registrarse o iniciar sesión.  
2. Crear una incidencia desde **“Nuevo Reporte”**.  
3. Ver y gestionar incidencias propias en el panel de usuario.  
4. Como Encargado, revisar todas las incidencias y actualizar su estado en el panel de administración.[file:76]

