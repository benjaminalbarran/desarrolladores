# Timbrar desde PHP

Para poder ejecutar los ejemplos es necesario tener PHP instalado en la version 4.0.4 o superior.

## Parametros de prueba

- La URL de prueba es: **http://staging.diverza.com/stamp**

- El token de seguridad de prueba es: **ABCD1234**

- El RFC emisor de prueba es: **AAA010101AAA**

## Windows
Para ejecutar un timbrado de prueba unicamente ejecuta el script desde la linea de comandos usando:

```sh
# Timbrar
C:\> "C:\Program Files (x86)\PHP\v5.3\php.exe" timbrar.php

# Cancelar
1) Agregar el UUID del CFDI a cancelar en el archivo cancelar.php:5

2) C:\> "C:\Program Files (x86)\PHP\v5.3\php.exe" cancelar.php
```

**Nota** Es posible que el archivo php.exe se encuentre en una ruta distinta dependiendo de la configuración del sistema.

## Unix/Linux/OSX
Para ejecutar un timbrado de prueba unicamente ejecuta el script desde la terminal usando:

```sh
# Timbrar
$ php timbrar.php

# Cancelar
1) Agregar el UUID del CFDI a cancelar en el archivo cancelar.php:5

2) $ php cancelar.php
```