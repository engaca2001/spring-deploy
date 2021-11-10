# Despliegue de apps Spring Boot en Heroku

Crar archivo system.properties en el proyecto con el contenido :
' java.runtime.version=17'

1. Crear cuenta en Heroku.com y en Github.com 
2. Tener configurado Git en el ordenador 
     
     1. git config --global user.name "engaca2001"
     2. git config --global user.email engaca2001@hotmail.com
     3. (Estos comandos anteriores se ejecutan en gitbash)
3. Subir el proyecto a Github desde IntellIj IDEA desde la opcion : VCS -> share proyect on Github
4. Desde Heroku crear app y elegir método Github y buscar el repositorio subido 
5. Habilitar deploy automatico y ejecutar el Deploy