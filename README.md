# Final - Ingenieria 
 
**Alumno:** Pauwels, Gaston Camilo 
**DNI:** 46007864  echo. 
## Descripcion 
Proyecto minimo entregable: HTML simple servido por Nginx en Docker. 
 
## Archivos incluidos 
- index.html 
- Dockerfile 
- README.md 
 
## Comandos Docker usados 
docker build -t final-ingenieria . 

docker run -d -p 8080:80 --name final-container final-ingenieria 
 
## URL 
 http://localhost:8080
