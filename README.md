# 💪 Proyecto de base de datos de Gimansio
----
Este proyecto de base de datos para un gimnasio busca optimizar la gestión de miembros, empleados, clases y pagos. Su objetivo es centralizar la información para automatizar procesos y facilitar la toma de decisiones.✨

-----
# ✨Objetivos: 
**1.** Optimizar la gestión de membresías y pagos.
**2.** Automatizar la programación de clases y el registro de asistentes.
**3.** Centralizar la información de miembros y empleados para mejorar la toma de decisiones.

----
# 🤖Tecnologias que usaria:

* MySQL: Para almacenar los datos.
* Python: Interactuar con la base de datos.
* Visual Studio Code:Gestionar todo el proyecto.

----
>"Organizar la información no es solo un fin, sino el punto de partida para el crecimiento."

# Link 
[Enlace a nuestra pagina web 💪](https://github.com/13492942/Base-de-datos-de-gimnasio.git)

=="Construye la base hoy, para que el éxito se construya sobre ella mañana."==
!["Construye la base hoy, para que el éxito se construya sobre ella mañana."](archivos/visual-studio-code-banner-image.jpg)

# Codigo
```sql
CREATE DATABASE gimnasio;
USE gimnasio;

CREATE TABLE miembros (
    id_miembro INT PRIMARY KEY AUTO_INCREMENT,
    nombre VARCHAR(50) NOT NULL,
    correo VARCHAR(100) UNIQUE NOT NULL
);
```
