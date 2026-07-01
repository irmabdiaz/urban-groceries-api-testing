# Urban Groceries |Manual & API Testing Project
Urban Groceries es una aplicación de comercio electrónico utilizada como entorno de práctica para aplicar técnicas de Manual Testing y API Testing en un escenario similar al de un proyecto real. 

## 🎯 Objetivo del Proyecto
Validación del funcionamiento de los endpoints REST de la aplicación Urban Groceries mediante pruebas funcionales, verificando respuestas HTTP, estructura JSON, manejo de errores y reglas de negocio para identificar posibles defectos antes de su liberación.

## 🛠️ Tecnologías y Herramientas
- **Herramientas de Pruebas**: Postman (Colección en formato JSON adjunta en el repositorio).
- **Validaciones**: Códigos de estado HTTP (200, 201, 400, 404), validación de esquemas JSON, tiempos de respuesta y payloads.
- **Entornos**: Configuración de variables dinámicas de entorno para simular peticiones en tiempo real.

## 📈 Cobertura de Pruebas Realizadas
- **Pruebas Positivas**: Verificación exitosa en la creación de kits de productos, adición de artículos al carrito de compras y cálculo correcto de costos de entrega.
- **Pruebas Negativas**: Evaluación del manejo de errores del servidor al enviar IDs de productos inexistentes, payloads vacíos o cantidades negativas en las órdenes.
- **Validación de Datos**: Confirmación de la estructura del backend para asegurar que las respuestas devuelvan objetos JSON consistentes.

## 💼 Habilidades Aplicadas
- API Testing
- Manual Testing
- REST API
- Postman
- JSON Validation
- HTTP Status Codes
- Test Case Design
- Bug Reporting

## 📚 Aprendizajes Obtenidos
- Diseñé y ejecuté escenarios de prueba para endpoints REST.
- Validé códigos de estado HTTP y la estructura de respuestas JSON.
- Probé escenarios positivos y negativos utilizando Postman.
- Fortalecí mis habilidades para identificar y documentar defectos de manera clara.
- Comprendí la importancia de validar reglas de negocio y respuestas del backend antes de la liberación de una aplicación.

## 🚀 Cómo ejecutar las pruebas en Postman
1. Descarga el archivo de la colección `.json` de este repositorio.
2. Abre la aplicación de **Postman**.
3. Haz clic en el botón **Import** (Importar) en la esquina superior izquierda y selecciona el archivo descargado.
4. Ejecuta la suite completa utilizando el **Collection Runner** de Postman para ver los resultados de las aserciones de manera automatizada.
