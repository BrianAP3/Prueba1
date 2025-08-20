# Guía Básica de PHP

## ¿Qué es PHP?

PHP (Hypertext Preprocessor) es un lenguaje de programación de código abierto ampliamente utilizado en el desarrollo web. PHP es especialmente adecuado para la creación de páginas web dinámicas, que interactúan con bases de datos y procesan formularios.

## Requisitos

Para comenzar a usar PHP, necesitas:

- Un servidor web como Apache o Nginx.
- PHP instalado en tu máquina (si aún no lo tienes, puedes descargarlo desde [php.net](https://www.php.net/downloads.php)).
- Un sistema de gestión de bases de datos como MySQL o MariaDB (si estás trabajando con bases de datos).

## Instalación

1. **Instalar PHP**:
   - Si usas Windows, puedes descargar XAMPP (que incluye Apache, MySQL y PHP) desde [https://www.apachefriends.org/es/index.html](https://www.apachefriends.org/es/index.html).
   - En Linux, puedes instalar PHP usando el comando:  
     ```bash
     sudo apt install php libapache2-mod-php
     ```
2. **Verificar la instalación**:
   - Abre la terminal o línea de comandos y escribe:
     ```bash
     php -v
     ```
     Deberías ver la versión de PHP instalada.

## Primer Script PHP

1. Crea un archivo llamado `index.php`.
2. Abre el archivo en un editor de texto y agrega lo siguiente:

```php
<?php
  echo "¡Hola, Mundo!";
?>
