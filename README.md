<img width="1600" height="900" alt="Captura de pantalla (35)" src="https://github.com/user-attachments/assets/07389215-c5fc-4e69-83a3-3f7ad3df8333" />
Sistema de Registro de Empleados
📋

Descripción del Proyecto
Sistema de gestión de empleados desarrollado en Python con interfaz gráfica Tkinter y base de datos MySQL. Permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre los registros de empleados de una empresa.

 ## ✨ Características Principales
Interfaz gráfica intuitiva con Tkinter

Conexión segura a MySQL con consultas parametrizadas

Gestión completa de empleados: agregar, visualizar y eliminar

Validación de datos en tiempo real

Arquitectura MVC (Modelo-Vista-Controlador)

Código modular y escalable

## 🛠️ Tecnologías Utilizadas
Python 3.x

Tkinter (Interfaz gráfica)

MySQL Connector (Base de datos)

MySQL Server (Motor de base de datos)


## 🚀 Instalación y Configuración

Prerrequisitos
Python 3.6 o superior instalado

MySQL Server instalado y ejecutándose

Tkinter (generalmente incluido con Python)


    Crear la base de datos en MySQL:

    CREATE DATABASE empresa_db;
    USE empresa_db;

    CREATE TABLE empleados (

    id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100) NOT NULL,
    sexo ENUM('Masculino', 'Femenino', 'Otro') NOT NULL,
    correo VARCHAR(150) NOT NULL UNIQUE,
    fecha_creacion TIMESTAMP DEFAULT CURRENT_TIMESTAMP
    );
    
## 2. Configurar conexión en el código:
Editar las credenciales en el archivo main.py:

    ##python
    db_config = {

    "host": "127.0.0.1",      # o "localhost"
    "user": "root",           # tu usuario MySQL
    "password": "tu_password", # tu contraseña MySQL
    "database": "empresa_db"
    }
# Creador por LuisSrzuwuaña123pepinocontajin
