# statistics-playground

Clonar el repo localmente y, teniendo ya instalado Docker, levantar los servicios con `docker compose up` (desde la terminal) o bien usando Docker Desktop u otro entorno como VS Code.

Si todo sale ok, deberían poder acceder a:
* JupyterLab http://localhost:8888/
* RStudio http://localhost:8787/
* Metabase http://localhost:3000/

El repo incluye una carpeta _mysql_ con lo necesario para instalar la base de datos sakila https://dev.mysql.com/doc/sakila/en/sakila-structure.html, muy útil para practicar SQL

El servicio de rstudio se construye a partir de una imagen personalizada con todas las librerías utilizadas en las materias Análisis y Métodos Estadísticos, y Métodos No Paramétricos, de la carrera Lic. en Estadística (UNTREF).
