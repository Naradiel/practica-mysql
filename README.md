# Práctica BBDD | Samsung Desarrolladoras 2023

## Descripción del proyecto
Se deberá entregar únicamente el archivo .sql que contenga la tabla USUARIO con los campos ID, NOMBRE, APELLIDO, EMAIL ”.

El campo ID será la Primary Key, autoincrementado.

Los campos NOMBRE, APELLIDO, EMAIL serán Varchar(20).

## Dependencias
- [MySQL](https://www.mysql.com/) - The world's most popular open source database

## Instrucciones de instalación
1. **Clona** este repositorio:
   ```sh
   git clone https://github.com/Naradiel/practica-mysql.git
      ```
2. **Accede al directorio del repositorio:** Navega al directorio del repositorio clonado ejecutando el siguiente comando:
   ```sh
   cd practica-mysql
      ```
3. **Importa el archivo .sql:** Asegúrate de tener acceso al servidor de bases de datos MySQL. Ejecuta el siguiente comando para importar el archivo usuario.sql en tu servidor:
   ```sh
   mysql -u <USUARIO> -p <NOMBRE_DE_LA_BASE_DE_DATOS> < usuario.sql
      ```
    Reemplaza <USUARIO> con el nombre de usuario de tu base de datos y <NOMBRE_DE_LA_BASE_DE_DATOS> con el nombre de la base de datos en la que deseas importar el archivo .sql. 

4. **Verifica la importación:** Una vez completada la importación, puedes verificar si el archivo .sql se ha importado correctamente en tu base de datos MySQL.
  
## Licencia
Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License. See `LICENSE` for more information.
