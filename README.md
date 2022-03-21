## Sensor MAX30102

## Sensor MLX90614

El procedimiento para utilizar el sensor de temperatura se enlista a continuación:

Paso 1. Actualizar Raspberry Pi con los comandos:
> sudo apt-get update
> 
> sudo apt-get upgrade


Paso 2. Activar el I2C:
> sudo raspi-config

Seleccione la opción 3 (Interfaces), luego la opción 5 (Activar I2C) y por ultimo Finish. Reinicie la rasberry pi.

Paso 3. Verificar que esten instalados python y pip:

> python --version
> 
> pip --version
