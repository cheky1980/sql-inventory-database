1_ SQL Inventory Database

Este proyecto consiste en el diseño e implementación de una base de datos en SQL Server para la gestión de productos y categorías.

2_ Tecnologías utilizadas

* SQL Server
* SQL (T-SQL)

3_ Estructura del proyecto

* `crear_base_de_datos.sql`: creación de la base de datos
* `insertar_datos.sql`: inserción de datos
* `consultas.sql`: consultas SQL (SELECT, filtros, LIKE, IN)
* `actualizaciones.sql`: sentencias UPDATE
* `procedimientos_almacenados.sql`: stored procedures

4 Relación de tablas

* Un producto pertenece a una categoría
* Relación mediante clave foránea (`CAT_ID`)

5_ Funcionalidades implementadas

* Creación de base de datos
* Inserción de datos
* Consultas con filtros
* Uso de LIKE e IN
* Actualización de registros
* Stored Procedures
* JOIN entre tablas

6_ Ejemplo de consulta

```sql
SELECT P.PROD_NOM, C.CAT_NOM
FROM TM_PRODUCTO P
INNER JOIN TMCATEGORIA C 
ON P.CAT_ID = C.CAT_ID;
```

7_ Autor

Sergio (cheky1980)

---

Proyecto en constante mejora
