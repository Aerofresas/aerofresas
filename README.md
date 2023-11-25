# AEROFRESAS

[![documentacion imagen](https://github.com/Aerofresas/aerofresas/blob/main/poster.png?raw=true "documentacion imagen")](# "documentacion imagen")

### AEROFRESAS, cultivo didáctico

Presentación el proyecto: [https://youtu.be/kD3DB3PJZvg ](https://youtu.be/RUXNvCBa0ak)

Funcionamiento del Proyecto: [https://youtu.be/9s7RzT5pfzQ](https://youtu.be/9s7RzT5pfzQ)

**Aerofresas** Aerofresas es un proyecto educativo que utiliza la aeroponía para cultivar de manera sostenible, destacando la eficiencia en el uso del agua. Con enfoque en tecnologías innovadoras, busca sensibilizar sobre la mitigación de los impactos del cambio climático en comunidades académicas, promoviendo la conciencia ambiental y la capacidad de adaptación.

- **Didáctico**: Promueve aprendizaje práctico y participativo para comprender tecnología agrícola avanzada.

- **Asequible**: Utiliza materiales reciclados y diseño económico para facilitar acceso general.

- **Sostenible**: Encaminado al cumplimiento el [Objetivo de Desarrollo Sostenible # 13][Objetivo de desarrollo sostenible # 13].

## Documentación

El código de AEROFRESAS está dividido en 3 partes. **En cada uno de los repositorios se encuentra documentación más detallada**.

- **[pipe-arduino:][pipe-arduino]** Sketch de Arduino programado en C++. Su función es recolectar mediante sensores y posteriormente enviar al servidor la humedad, temperatura y luminosidad del invernadero y verifica cada determinado tiempo si en el servidor hay una petición pendiente para activar una bombilla o una bomba de agua. Este corre en cualquier placa de desarrollo, se recomienda ESP 32.

- **[pipe-server:][pipe-server]** Servidor escrito con Node.js. Este recibe los datos (humedad, temperatura, luminosidad) de la placa y los envía al frontend del usuario mediante una API. Mediante la misma API recibe las peticiones (activar bombilla, activar bomba de agua) del usuario para que la placa procese y ejecute. Corre en cualquier servicio de hosting que soporte Javascript.

- **[pipe-frontend:][pipe-frontend]** Página web programada con React. Muestra los datos del invernadero y envía las peticiones al servidor. Es hosteado mediante Github Pages.

## Autores

AEROFRESAS esta dirigido por **[Julian Franco][julian franco]**, **Zaida Guzman** y **[David Hurtado][david hurtado]**, estudiantes del **[Colegio Agustiniano Norte][colegio agustiniano norte]**, apoyados por el profesor **[William Andres Granada Campos][william andres granada campos]**.

[objetivo de desarrollo sostenible # 13]: https://www.un.org/sustainabledevelopment/es/climate-change-2/ "Objetivo de Desarrollo Sostenible # 13"
[david hurtado]: https://santigo171.github.io/ "David Hurtado"
[william andres granada campos]: https://www.linkedin.com/in/william-andres-granada-campos-b4017116/ "William Andres Granada Campos"
[colegio agustiniano norte]: https://agustinianonorte.edu.co/ "Colegio Agustiniano Norte"
[pipe-arduino]: https://github.com/Proyecto-Pipe/pipe-arduino "pipe-arduino"
[julian franco]: https://www.instagram.com/Julianfranco_07/ "Julian Franco"
[pipe-server]: https://github.com/Proyecto-Pipe/pipe-server "pipe-server"
[pipe-frontend]: https://github.com/Proyecto-Pipe/pipe-frontend "pipe-frontend"
