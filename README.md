## Configuración general para utilizar los sensores de temperatura y concentración de oxigeno.


Paso 1. Actualizar Raspberry Pi con los comandos:
> sudo apt-get update
> 
> sudo apt-get upgrade


Paso 2. Activar el I2C:
> sudo raspi-config

Paso 3. Seleccione la opción 3 (Interfaces), luego la opción 5 (Activar I2C) y por ultimo Finish. Reinicie la rasberry pi.

Paso 4. Verificar que esten instalados python y pip:

> python --version
> 
> pip --version

Con la configuración realizada, esta listo para probar los sensores.

## Sensor MLX90614
### Conexión entre la Raspberry pi y MLX90614.

|Raspberry pi   |MLX90614   |
| ------------ | ------------ |
|5 V   |VIN   |
|GND   |GND   |
|SCL1   |SCL   |
|SDA1   |SDA   |

## Sensor MAX30102


