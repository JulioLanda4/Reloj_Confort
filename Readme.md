# Reloj Inteligente IoT para Datos de Confort Térmico

Este proyecto consiste en un **reloj inteligente IoT** desarrollado con tecnologías abiertas para recopilar datos sobre el confort térmico. El dispositivo realiza encuestas simplificadas cada hora, específicamente a los 30 minutos de cada hora, y mide variables fisiológicas como la **temperatura de la piel en la muñeca** y el **ritmo cardíaco**. Los datos se envían a la plataforma IoT **Thingsboard** para su almacenamiento.

## Estructura del Repositorio

El repositorio está organizado en las siguientes carpetas:

1. **Arduino**: Contiene todas las librerías y configuraciones necesarias para poner en funcionamiento la tarjeta **XIAO ESP32C3**, la pantalla y otros componentes esenciales del proyecto.

2. **Carcasa**: Incluye los archivos **FCstd** para la impresión 3D de la carcasa del reloj.

3. **Esquemáticos**: Proporciona los esquemas necesarios para la construcción y montaje del dispositivo.

4. **Smartwatch_App**: Contiene el código fuente completo del proyecto de Arduino, incluyendo todos los recursos necesarios para el funcionamiento del reloj inteligente.

5. **Thingsboard**: Incluye todo lo necesario para descargar y manipular los datos mediante una libreta de **Jupyter Notebook**.

## Autores

- **Julio Landa** - [jclalo@ier.unam.mx](mailto:jclalo@ier.unam.mx)
- **Guillermo Barrios** - [gbv@ier.unam.mx](mailto:gbv@ier.unam.mx)

## Licencia

Este proyecto está licenciado bajo la **GNU General Public License v3.0**.

---

Si tienes preguntas o necesitas asistencia, no dudes en ponerte en contacto con los autores.
