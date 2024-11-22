# EntregaProyecto
Taller para entregar tarea de back y front 

Guía para levantar Backend y Frontend localmente

1. Backend (Back-end)

Paso 1: Clonar el repositorio
Si aún no tienes el repositorio clonado:

git clone https://github.com/Cris271MX/EntregaProyecto

Paso 2: Configurar el entorno
1. Archivos de configuración:
    - Busca un archivo como .nenv.example ya que esta es la varible de entorno para levantar el back-end
   

2. Instalar dependencia:
    - Se usa Python:
        pip install -r requirements.txt


Paso 3: Ejecutar el backend
    - Inicia el servidor:
        - Python (Django/Flask):
            python manage.py runserver

    - Verifica que el backend esté corriendo en el puerto correspondiente, como http://localhost:5000.

2. Frontend (Front-end)

Paso 2: Instalar dependencias
1. Instala las dependencias con el gestor de paquetes (por ejemplo, npm o yarn):
    npm install
    o
    yarn install

Paso 3: Configurar el entorno
1. Busca un archivo como .env.example y configúralo. Por ejemplo:
    cp .env.example .env
2. Llena las variables de entorno necesarias (como la URL del backend).

Paso 4: Ejecutar el frontend
1. Inicia el servidor de desarrollo:
    npm run dev
    o
    yarn dev

2. Por defecto, el servidor corre en http://localhost:5000 (o el puerto configurado).

3. Verificar la conexión
1. Abre el navegador y verifica:
    - Backend: http://localhost:<puerto_backend>
    - Frontend: http://localhost:<puerto_frontend>

2. Verifica que el frontend pueda consumir los servicios del backend correctamente.

