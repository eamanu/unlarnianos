# UNLARNIARNOS

Este proyecto está basado en [FlaskBB](https://github.com/flaskbb/flaskbb). Para más información sobre este visitar su página.

## Levantar el proyecto

Para levantar el proyecto en modo *desarrollo* se deben seguir los siguientes pasos:

* Crear un ambiente virtual. Esto se lo puede hacer mediante *virtualenvwrapper* (probado), o usando `python3 -m venv` (no probado).
* Crear la configuración
    * `make devconfig`
* Instalar las depedencias y flaskbb en sí:
    * `make install`
* Ejectutar el server en modo desarrollo:
    * `make run`
* Visitar [localhost:5000](http://localhost:5000)


## License

Este proyecto es GPL
