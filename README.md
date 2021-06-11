# Pagina_web

Actualmente hay un servidor de Django vacío

Los pasos seguidos para su creación fueron

### Crear venv o virtual enviroment
> py -m venv .

### Ambientarse en el venv 

> .\Scripts\activate

### Instalar django 

> pip install django

### Crear projecto 

> django-admin.exe startproject EAWebPage .

### Hacer commit en la base de datos

> py .\manage.py migrate

### Crear superusuario 

> py .\manage.py createsuperuser

Username EAsudo

password: EAserver123!

### Para correr el servidor, basta con clonar el proyecto en sus computadoras 
> git clone https://github.com/ElectrizArteUCR/Pagina_web.git 

### En una terminal, puede ser powershell en windows entran a la carpeta donde clonaron el repositorio y se ambientan en el venv 
> .\Scripts\activate

### Entran a la carpeta "root" que es donde está el archivo "manage.py" en este caso es src y corren el servidor
> cd src
> py manage.py runserver

### Van a ver una linea que les da la dirección del server y pueden entrar y ver la página default de django
Starting development server at http://127.0.0.1:8000/

### Si lo desean pueden abrir el servidor en otro puerto si ya tienen otro servidor corriendo en el 8000
> py manage.py runserver 8080

### Y pueden acceder a la pagina de admin agregando admin en el path del url anterior y  los credenciales mostrados arriba podrán ver la consola admin default de django donde se puede ver la base de datos y más adelante las apps! :)
