# UTILS
En la arquitectura limpia (Clean Architecture), la carpeta "utils" generalmente 
se utiliza para almacenar funciones o clases de utilidad que no encajan claramente 
en ninguna de las capas principales de la arquitectura, como la capa de dominio, 
la capa de aplicación o la capa de infraestructura. Esta carpeta se utiliza para 
organizar código que proporciona funcionalidad genérica que puede ser utilizada en 
toda la aplicación sin estar fuertemente acoplada a una capa específica.

Algunos ejemplos de lo que podría encontrar en la carpeta "utils" en una aplicación que sigue Clean Architecture incluyen:

1. Funciones de manipulación de datos: Funciones que realizan operaciones comunes en datos, como formatear fechas, convertir tipos de datos, realizar cálculos matemáticos, etc.

2. Funciones de validación: Funciones que verifican la validez de datos o entradas, como comprobar si una dirección de correo electrónico es válida, validar números de teléfono, etc.

3. Utilidades de manejo de archivos: Funciones para trabajar con archivos, como leer y escribir archivos, manipular rutas de archivo, etc.

4. Funciones de ayuda general: Funciones que ofrecen utilidad en toda la aplicación, como funciones para generar identificadores únicos, funciones para formatear texto de manera específica, funciones para manejar excepciones de manera consistente, entre otras.

5. Funciones de seguridad: Funciones relacionadas con la seguridad de la aplicación, como funciones para cifrar y descifrar datos, autenticación de usuarios, manejo de contraseñas, etc.

Es importante destacar que la carpeta "utils" debe utilizarse con moderación y de manera organizada. No debe convertirse en un "cubo de basura" para código no estructurado. Las funciones y clases que se coloquen en esta carpeta deben ser lo más genéricas y reutilizables posible para que puedan ser utilizadas en diferentes partes de la aplicación, manteniendo así el principio de separación de preocupaciones y la modularidad que promueve Clean Architecture.