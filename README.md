# Respuestas
RETO 01 

Casos de Prueba para Registro (Frontend y Backend) 

Validación del Correo Electrónico: 

El correo debe contener un @ para ser válido. 

Verificar que el sistema muestra un error si el correo no contiene @. 

Verificar que el sistema muestra un error si el campo de correo está vacío. 

Validación de Contraseña: 

La contraseña debe tener al menos 5 caracteres. 

Verificar que el sistema muestra un error si la contraseña es menor a 5 caracteres. 

Verificar que el sistema muestra un error si el campo de contraseña está vacío. 

Campos Obligatorios: 

Verificar que tanto el correo como la contraseña sean campos requeridos. 

Mensajes de Error: 

Verificar que los mensajes de error sean claros y visibles para el usuario cuando los campos no sean válidos. 

 

Casos de Prueba para Login (Frontend y Backend) 

Validación del Correo Electrónico: 

El correo debe contener un @ para ser válido. 

Verificar que el sistema muestra un error si el correo no contiene @. 

Verificar que el sistema muestra un error si el campo de correo está vacío. 

Validación de Contraseña: 

La contraseña debe tener al menos 5 caracteres. 

Verificar que el sistema muestra un error si la contraseña es menor a 5 caracteres. 

Verificar que el sistema muestra un error si el campo de contraseña está vacío. 

Campos Obligatorios: 

Verificar que tanto el correo como la contraseña sean campos requeridos. 

Mensajes de Error: 

Verificar que los mensajes de error sean claros y visibles para el usuario cuando los campos no sean válidos. 

 

Técnica de Diseño de Casos de Prueba 

Dado que los requisitos se basan en validaciones específicas de los campos (correo y contraseña), la técnica de diseño de casos de prueba que mejor se adapta es: 

Partición de Equivalencias: Esta técnica se utiliza para reducir la cantidad de casos de prueba al dividir los valores válidos e inválidos de los campos. Ejemplo: 

Correo: Validar un correo con @, un correo sin @, y un correo vacío. 

Contraseña: Validar una contraseña con más de 5 caracteres, menos de 5 caracteres, y una contraseña vacía. 

Análisis de Valor Frontera: Validar el límite exacto de 5 caracteres para la contraseña, probando con 4 y 5 caracteres. 

Identificación y Registro de Bugs o Mejoras 

Bugs: 

Error en la Validación del Correo: El sistema no valida correctamente que el correo contenga un @, o permite correos vacíos, esto debe ser corregido. 

Validación de Contraseña Incompleta: El sistema permite contraseñas con menos de 5 caracteres o vacías, este comportamiento también debe ser corregido. 

Errores de Mensajes de Validación: Los mensajes de error no son claros o no se muestran al usuario, será necesario corregir esta parte para que sea más amigable y comprensible. 

Mejoras: 

Mejora en la UI/UX: Asegurar que la validación de los formularios sea intuitiva y el usuario reciba retroalimentación clara y rápida. 

Funcionalidad de Recordar Usuario: Implementar una opción para que los usuarios puedan ser recordados durante futuras sesiones sin tener que volver a ingresar sus credenciales, mejorando la experiencia del usuario. 

RETO 2 

 

Entorno de Trabajo y niveles de pruebas 

 

 

En el ambiente de desarrollo se aplica: 

Pruebas Unitarias: Pruebas de componentes desarrollados por los developers 

Pruebas de Integración: Pruebas de comunicación entre componentes desarrollados por los developers 

 

 

En el ambiente de QA se aplica: 

Pruebas de sistema: Validar la integración completa de los componentes desplegados por desarrollo por consiguiente su correcto funcionamiento. 

API Test: Prueba donde el equipo de desarrollo hace entrega de las colecciones de las APIs entregadas al equipo de calidad para validar el funcionamiento de estas y validar las respuestas de las APIs emitan correctamente. Por consiguiente, se documenta las respectivas validaciones 

En el ambiente de Produccion se aplica: 

Pruebas GUI o de Sistema: Solo se aplica para validar las funciones primarias o detectar algunos defectos que podrían haber pasado desapercibidos en etapas anteriores. 

 

RETO 03 

Se ordena los defectos segun priorizacion: 

Credenciales no cifradas: Riesgo de compromiso de seguridad y protección de datos. 

Transacciones no reflejadas: Impacto en la integridad de los datos y la transparencia de las transacciones. 

Ancho de banda de 100 MB: Accesibilidad limitada para usuarios con conexiones lentas. 

Precios sin variación en monedas: Afecta la usabilidad para usuarios internacionales. 

Foros sin registrar comentarios: Deteriora la experiencia de soporte y satisfacción del usuario. 

Errores ortográficos: Afecta la percepción de profesionalismo, pero no impacta funcionalmente. 

 

RETO 04 

Las alternativas o mejoras que podrían aplicarse para alinearse mejor con las prácticas de Agile Testing: 

Pruebas de rendimiento: Mantén el uso del entorno de usuarios finales, pero incluye pruebas en preproducción para simular variaciones en la carga. 

Pruebas de humo: Automatiza las pruebas de humo para hacerlas más rápidas y repetibles, mejorando la eficiencia del equipo. 

Pruebas de regresión: Expande las pruebas de regresión para cubrir más que solo los módulos afectados, utilizando un enfoque de regresión continua. 

Gestión de casos de prueba: Transita de Excel a una herramienta de gestión de pruebas para un seguimiento y colaboración más eficiente, y evita eliminar casos de prueba en cada iteración. 

Involucramiento temprano: Fomenta el uso de TDD o BDD para definir las pruebas incluso antes de escribir el código, asegurando que el equipo de pruebas esté alineado desde el principio. 

 

 
