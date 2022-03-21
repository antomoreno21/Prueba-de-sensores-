#Sensor MAX30102

#Sensor MLX90614
Actualizar Raspberry Pi
> sudo apt-get update

> sudo apt-get upgrade

Activar el I2C
> sudo raspi-config
> 3 Interfaces
> 5 Activar I2C
> Finish
> Reiniciar sudo reboot

Comprobar python y pip. Verificar que esten instalados. Para ello, nos debe arrojar alguna version.
> python --version
> pip --version
