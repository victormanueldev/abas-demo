# ABAS SOFTWARE 

ABAS es un software para el control interno de una empresa de control de plagas, ABAS es capaz de 
tener una base de datos de clientes, agendar citas para control o visitas tecnicas y llamadas para 
la fidelización de clientes.

## Requerimientos de instalación
- XAMPP (PHP v7+, MYSQL 5.8)
- Git

## Instalación

### 1. Installar composer 
- Descargar de https://getcomposer.org/Composer-Setup.exe
- Instalar normalmente

### 2. Clonar el repositorio de código
- Entrar a la ruta de instalacion del xammp en C:\xampp\htdocs
- Ejecutar el comando de clonación del repositorio de código en CMD o Simbolo del Sistema

```
$ git clone https://github.com/victormanueldev/abas-demo.git
```

### 3. Instalar las dependencias de la aplicación
- Entrar a la carpeta del repositorio clonado en el paso anterior
- Ejecutar el comando de actualizacion de dependencias de composer en CMD o Simbolo del Sistema

```
$ composer install
```

### 4. Crear la base de datos en MYSQL
- Crear la base de datos en mysql con el nombre "abas_bd"

### 5. Migrar la base de datos de la aplicación
- Ejecutar el comando desde el CMD:

```
$ php artisan migrate --seed
```
### 6. Ejecutar la aplicación
- Ejecutar el comando desde el CMD:

```
$ php artisan serve
```

Luego de realizar estos pasos, puedes ingresar al http://localhost:8000 donde se estará ejecutando la aplicación.