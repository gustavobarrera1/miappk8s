Practica Bootcamp DevOps - Desafio 3 
# Ejecucion mediante minikube - Esto puede variar dependiendo del entorno de k8s que utilizemos
* Debemos ingresar a minikube para crear la ruta del volumen persistente:

    <sub>minikube ssh</sub>
  
* Creación de las carpetas dentro de minikube:
  
    <sub>sudo mkdir -p /data/miapp</sub>

* Dar permisos de acceso a la carpeta de minikube:

    <sub>sudo chmod 777 /data/miapp</sub>

# Ejecución del deploy de kubernetes
* Una vez clonado el repositorio, dentro de la carpeta de trabajo ejecutamos:

    <sub>kubectl apply -f miapp-full.yaml</sub>

# Aclaración: Esta ejecución es posible mediante un pull a DockerHub de la imagen que previamente subida a la plataforma, dejo como backup el archivo Dockerfile que utiliza la imagen pública por cualquier falló.
# Documento para la instalación y configuración de Minikube para la creación de un cluster de Kubernetes: 
https://docs.google.com/document/d/14qgiJ3CBqk0qk5494DqK4yMQKxrEqEvgJNk-zxlEk24/edit?usp=sharing
