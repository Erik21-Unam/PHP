# Sistema-inscripcion-laravel
Sistema de inscripción a cursos realizado en Laravel v.4.2 

- Instalar Composer

- Copiar la carpeta `APPINSCRIPCIONCURSOS` a tu servidor local.

- Cambiarse al directorio `APPINSCRIPCIONCURSOS` y ejecutar el comando `composer install`

- Crear la base de datos `BDCursos`;

- Importar el archivo `bdcursos.sql` a la base de datos creada.

Editar los parametros del archivo `database.php` que se encuentra en la ruta `APPINSCRIPCIONCURSOS/app/config/`

```
'mysql' => array(
			'driver'    => 'mysql',
			'host'      => 'localhost',
			'database'  => 'BDCursos',
			'username'  => 'root',
			'password'  => '',
			'charset'   => 'utf8',
			'collation' => 'utf8_unicode_ci',
			'prefix'    => '',
		),
```


![Texto] (https://github.com/Erik21-Unam/Sistema-inscripcion-laravel/blob/master/basededatos/screenshot.PNG)
