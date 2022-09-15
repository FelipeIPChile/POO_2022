# POO_2022
Código de proyectos en Java Swing desarrollados en clases de POO para IP Chile año 2022

Script para creación de Tabla y Inserción de datos en BD

CREATE TABLE USUARIOS (RUT VARCHAR(10) NOT NULL, NOMBRE VARCHAR(300), APE_PATERNO VARCHAR(300), APE_MATERNO VARCHAR(300), CLAVE INTEGER NOT NULL, ACTIVO BOOLEAN NOT NULL, ROL VARCHAR(300) NOT NULL, PRIMARY KEY (RUT));

INSERT INTO DBIPCHILE.USUARIOS (RUT, NOMBRE, APE_PATERNO, APE_MATERNO, CLAVE, ACTIVO, ROL) 
	VALUES ('4321', 'Felipe', 'Perez', 'Reyes', 1234, true, 'USER');
INSERT INTO DBIPCHILE.USUARIOS (RUT, NOMBRE, APE_PATERNO, APE_MATERNO, CLAVE, ACTIVO, ROL) 
	VALUES ('1234', 'Francisco', 'Ruiz', 'Materno', 1234, true, 'Super Usuario');
