# Comandos
Para abrir psql en la consola de linux usar: sudo -u postgres psql
### Crear una tabla:
CREATE TABLE Producto(
id_producto SERIAL PRIMARY KEY,
nombre VARCHAR(25),
stock INT);
CREATE TABLE
### Ver la tabla:
\d
### comando para añadir atributos a la tabla
ALTER TABLE Producto
**ADD** precio NUMERIC(8,2);
### Comando para quitar atributos a la tabla
ALTER TABLE "Entidad"
DROP COLUMN "Atributo";

