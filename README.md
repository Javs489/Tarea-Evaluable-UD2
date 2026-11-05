
Link video: https://www.youtube.com/watch?v=GiDCK5XIXZw

El repositorio contiene los scripts de automatización y configuración necesarios para levantar y fortificar ambos entornos docker-compose.yml: Orquestador de contenedores para MariaDB y PostgreSQL con redes estáticas e IPs fijas.
config/99-custom.cnf Configuración personalizada de MariaDB para la carga del plugin de autenticación ed25519.
pg_hba.conf es el Firewall lógico de PostgreSQL con restricciones de acceso y cifrado scram-sha-256.
scripts: Carpeta contenedora de los scripts de inicialización SQL (script_mariadb_fintech_core.sql y analítico).

