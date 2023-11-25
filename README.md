# AEROFRESAS

[![documentacion imagen](https://github.com/Aerofresas/aerofresas/blob/main/poster.png?raw=true "documentacion imagen")](# "documentacion imagen")

### AEROFRESAS, cultivo didáctico

Presentación el proyecto: [https://youtu.be/kD3DB3PJZvg ](https://youtu.be/RUXNvCBa0ak)

Funcionamiento del Proyecto: [https://youtu.be/9s7RzT5pfzQ](https://youtu.be/9s7RzT5pfzQ)

**Aerofresas** Aerofresas es un proyecto educativo que utiliza la aeroponía para cultivar de manera sostenible, destacando la eficiencia en el uso del agua. Con enfoque en tecnologías innovadoras, busca sensibilizar sobre la mitigación de los impactos del cambio climático en comunidades académicas, promoviendo la conciencia ambiental y la capacidad de adaptación.

- **Didáctico**: Promueve aprendizaje práctico y participativo para comprender tecnología agrícola avanzada.

- **Asequible**: Utiliza materiales reciclados y diseño económico para facilitar acceso general.

- **Sostenible**: Encaminado al cumplimiento el [Objetivo de Desarrollo Sostenible # 13][objetivo de desarrollo sostenible # 13][Objetivo de Desarrollo Sostenible # 6][objetivo de desarrollo sostenible # 6]

## Documentación

El código de AEROFRESAS está dividido en 3 partes. **En cada uno de los repositorios se encuentra documentación más detallada**.

- **[aerofresas-arduino:][aerofresas-arduino]** Sketch de Arduino programado en C++. Su función es recolectar mediante sensores y posteriormente enviar los datos a la pantalla oled de la humedad, temperatura del cultivo y activa los actuadores, bomba de aire, ventilador y bomba de riego de alta presión automaticamente segun los valores de los sensores
- **[arduino-esp01:][arduino-esp01]** Sketch de Arduino programado en C++. Su función es enviar los valores que recibe del microcontrolador, para subirlos al servidor en FIREBASE.
- **[aerofresas-app:][aerofresas-app]** Aplicación Android Studio con 3 pantallas: la primera para registro e ingreso de usuarios, la segunda que solicita datos al servidor y los muestra, y la tercera que proporciona información detallada sobre Aerofresas.

## Autores

AEROFRESAS esta dirigido por **Lina Marcela Morales**, **Jhon Alexander Aguirre** y **Mateo Alejandro Cardona**, estudiantes de **I.E. Juan Pablo Gomez Ochoa**, apoyados por el profesor **Leao Simón Rodríguez**.

[objetivo de desarrollo sostenible # 13]: https://www.un.org/sustainabledevelopment/climate-change/ "Objetivo de Desarrollo Sostenible # 13"
[objetivo de desarrollo sostenible # 6]: https://www.un.org/sustainabledevelopment/es/water-and-sanitation/ "Objetivo de Desarrollo Sostenible # 6"
[aerofresas-arduino]: https://github.com/Proyecto-Pipe/pipe-arduino "pipe-arduino"
[arduino-esp01]: https://github.com/Proyecto-Pipe/pipe-server "pipe-server"
[aerofresas-app]: https://github.com/Proyecto-Pipe/pipe-frontend "pipe-frontend"
