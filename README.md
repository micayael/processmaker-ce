processmaker-ce
===============


# Para iniciar por primera vez los servicios
docker-compose up -d

# Para revisar el estado de los servicios
docker-compose ps

# Para levantar los servicios
docker-compose start

# Para bajar los servicios
docker-compose stop

# Para eliminar los servicios
docker-compose down

# Para revisar los logs
docker-compose logs -f

processmaker-config
-------------------

Host Name: 172.17.0.1
Port: 3316
Username: root
Password: mypassword

phpmyadmin
----------

url: http://localhost:8281
host: mariadb
user: root
password: mypassword
database: wf_workflow

processmaker
------------

url: http://localhost:8201/
user: admin
password: admin
workspace: workflow
