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

### Prueba del sensor
Paso 1. Descargue el siguiente codigo: [MLX90614](https://github.com/antomoreno21/Prueba-de-sensores-/tree/main/MLX90614 "MLX90614").

Paso 2. Instalar la biblioteca del sensor MLX90614 con el comando:
> pip install pyMLX90614

Paso 3. Abrir una terminal donde se encuentre el archivo descargado del paso 1. Ejecute en dicha terminal el comando:
> python MLX90614.py

Con esto finaliza la prueba del sensor, en la terminal deberá mostrarse la temperatura en grados centigrados.

## Sensor MAX30102


