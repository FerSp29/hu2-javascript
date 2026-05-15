# Gestión de Productos y Estructuras de Datos en JavaScript

Este proyecto es una práctica técnica que se enfoca en el manejo de estructuras de datos fundamentales en JavaScript por ejemplo: **Objetos**, **Sets** (Conjuntos) y **Maps** (Mapas). El código demuestra cómo organizar, filtrar e iterar sobre datos de una manera eficiente.

## 📋 Descripción del Proyecto

El script realiza una serie de tareas para poder gestionar un inventario simplificado de productos y manipular las colecciones de datos numéricos. Se incluyen validaciones de datos y diferentes métodos de iteración (ciclos).

## 🚀 Funcionalidades Principales

### 1. Gestión de Objetos (Productos)
- El almacenamiento de productos utilizando un objeto literal donde cada clave es un identificador único.
- Cada producto contiene propiedades como lo son el `id`, `nombre` y `precio`.

### 2. Manipulación de Sets (Conjuntos)
- Creación de un `Set` a partir de un array con duplicados para demostrar la eliminación automática de los valores repetidos.
- Uso de métodos nativos:
  - `.add()`: Para la inserción de nuevos elementos.
  - `.has()`: Para verificar la existencia de un valor.
  - `.delete()`: Para remover ciertos elementos específicos.

### 3. Uso de Maps (Mapas)
- Relación de las categorías de productos con sus respectivos nombres.
- Implementación del método `.set()` y recorrido mediante el `.forEach()`.

### 4. Filtrado y Validación
- Validación de integridad de los datos: se verifica que los productos tengan un ID válido, un nombre no vacío y un precio coherente antes de que sean procesados.

## 🔄 Métodos de Iteración Utilizados

El proyecto implementa diversas formas de recorrer datos según la estructura:
- **for...in**: Utilizado para iterar sobre las propiedades de los objetos.
- **for...of**: Utilizado para recorrer los valores de un Set.
- **forEach()**: Utilizado para la lectura descriptiva de las claves y valores en un Map.

## 🛠️ Estructura de Archivos

- `index.html`: Archivo de entrada que enlaza el script para su visualización en el navegador.
- `main.js`: (O el nombre de tu archivo .js) Contiene toda la lógica de programación y manipulación de datos.

## 💻 Cómo ejecutar
1. Descarga los archivos del proyecto.
2. Abre el archivo `index.html` en tu navegador favorito.
3. Abre las **Herramientas de Desarrollador** (F12 o Clic derecho -> Inspeccionar).
4. Dirígete a la pestaña **Consola** para visualizar los resultados de las ejecuciones y las pruebas lógicas.
