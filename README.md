# Nodeca

Proyecto personal donde intento aprender nuevas tecnologías y practicar los conocimientos de lo ya aprendido. El proyecto esta dividido en tres partes: database, backend y frontend.

## Índice

- [Nodeca](#nodeca)
  - [Índice](#índice)
  - [Base de datos](#base-de-datos)
    - [Iniciar](#iniciar)
    - [Tecnologías](#tecnologías)

## Base de datos

### Iniciar

En la raíz del proyecto se encuentra el archivo `docker-compose.yml` el cual tiene un script para generar la base de datos, las tablas, sus relaciones y además importar los datos desde archivos csv (éstos archivos csv no se subirán al repositorio).

Para crear nuestro contenedor:

```bash
# En la raíz de nuestro proyecto...
docker-compose up
```

### Tecnologías

| Nombre                               | Detalles                                                                              |
| ------------------------------------ | ------------------------------------------------------------------------------------- |
| 🐋 [Docker](https://www.docker.com/) | Tecnología en contenedores que posibilita la creación y el uso de contenedores Linux. |
| 🐬 [MariaDB](https://mariadb.org/)   | Sistema de gestión de bases de datos derivado de MySQL con licencia                   |
