# Acceso a datos 01

---

# Instrucciones
Se han creado dos archivos en la carpeta *dockerfiles* para iniciar los motores *Oracle* y *MySQL*.

Dentro de la carpeta, ejecutar:
* docker compose -f oracle-compose.yaml up -d
* docker compose -f mysql-compose.yaml up -d

Se puede comprobar la conexión desde cualquier cliente. En el ejercicio se utiliza *DBeaver* para conectarse con las configuraciones y usuarios que figuran en los *compose*

La base de datos SQLite se crea directamente desde DBeaver y también se adjunta al repositorio *prueba_ad01.db*