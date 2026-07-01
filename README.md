# Urban Groceries API Testing Project

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

## 🚀 Cómo revisar y ejecutar las pruebas en tu Postman
1. Descarga el archivo de la colección `.json` de este repositorio.
2. Abre tu aplicación de **Postman**.
3. Haz clic en el botón **Import** (Importar) en la esquina superior izquierda y selecciona el archivo descargado.
4. Ejecuta la suite completa utilizando el **Collection Runner** de Postman para ver los resultados de las aserciones de manera automatizada.
