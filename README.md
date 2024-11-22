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
   

2. Instalar dependencias:
    - Si el backend usa Node.js:
        npm install
    - Si usa Python:
        pip install -r requirements.txt
    - Para otros entornos (Java, PHP, etc.), sigue las instrucciones del proyecto.

Paso 3: Iniciar la base de datos
    - Si el backend depende de una base de datos, asegúrate de que esté corriendo localmente o configurada en la nube.
    - Por ejemplo, para una base de datos PostgreSQL:
        docker-compose up -d  # Si hay un archivo docker-compose.yml
    - Alternativamente, inicia el servidor de tu base de datos localmente.

Paso 4: Ejecutar el backend
    - Inicia el servidor:
        - Node.js:
            npm run dev
        - Python (Django/Flask):
            python manage.py runserver
        - Java (Spring Boot):
            mvn spring-boot:run

    - Verifica que el backend esté corriendo en el puerto correspondiente, como http://localhost:3000.

2. Frontend (Front-end)

Paso 1: Clonar el repositorio
Si aún no tienes el repositorio clonado:

git clone https://github.com/usuario/repositorio-frontend.git
cd repositorio-frontend

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
