# Pruebas de API Petstore

Este repositorio contiene una colección de Postman para probar las funcionalidades de la API de Petstore (https://petstore.swagger.io).

## Contenido
- `petstore-api-tests.json`: Colección de Postman con las pruebas de la API.

## Funcionalidades Probadas
1. Crear un usuario.
2. Iniciar sesión con el usuario creado.
3. Listar todas las mascotas con estado "disponible".
4. Consultar los datos de una mascota específica.
5. Crear una orden (compra) para una mascota.
6. Cerrar sesión.

## Requisitos
- Postman (descargable desde https://www.postman.com/downloads/).
- Acceso a la API de Petstore (https://petstore.swagger.io).

## Cómo Usar
1. **Importar la colección**:
   - Abre Postman.
   - Ve a **Collections** y selecciona **Import**.
   - Carga el archivo `petstore-api-tests.json`.

2. **Configurar variables**:
   - Asegúrate de que las variables de colección estén configuradas:
     - `baseUrl`: `https://petstore.swagger.io/v2`
     - `username`: Un nombre de usuario único (por ejemplo, `testUser123`).
     - `petId`: Un ID de mascota válido.

3. **Ejecutar la colección**:
   - Ve a la colección `Petstore API Tests` y selecciona **Run Collection**.
   - Asegúrate de ejecutar las solicitudes en orden.
   - Revisa los resultados de los tests para confirmar que todas las pruebas pasen.

## Estructura de la Colección
La colección incluye las siguientes solicitudes, cada una con un test único:
1. **Crear Usuario**: Crea un nuevo usuario en la API.
2. **Hacer Login**: Inicia sesión con el usuario creado.
3. **Listar Mascotas Disponibles**: Obtiene todas las mascotas con estado "available".
4. **Consultar Mascota Específica**: Consulta los detalles de una mascota por su ID.
5. **Crear Orden**: Crea una orden de compra para una mascota.
6. **Hacer Logout**: Cierra la sesión del usuario.

## Notas
- Asegúrate de que la API de Petstore esté disponible al ejecutar las pruebas.
- Si encuentras errores, verifica que las variables de colección estén correctamente configuradas.
- Para más detalles sobre la API, consulta la documentación oficial: https://petstore.swagger.io.
