# Proyecto_Algoritmos

## Integrantes
- Maikol Vergara
- Victor Peñaranda
- Juliana Castro
- Valentina Leon
- Lukas Rodriguez
- Juan Perez
- Juan Barajas

## Herramienta
**UiPath Studio Open Source**

### Descripción
UiPath Studio es una herramienta avanzada para la **Automatización de Procesos Robóticos (RPA)**. Permite a los usuarios diseñar y desarrollar procesos de automatización de manera visual, utilizando una interfaz de usuario gráfica (GUI) intuitiva y fácil de usar.

## Paso a Paso del Proyecto
1. Establecer las tablas de los datos a extraer y crear dichas tablas.
2. Identificar el paso a paso para llegar hasta la información deseada.
3. Extraer y guardar cada dato en las tablas correspondientes.

## Estructura de Datos

### Hoja Cuentas_Busqueda
| Nombre Columna             | Descripción                                                       |
|----------------------------|-------------------------------------------------------------------|
| Nombre_Usuario             | Nombre de la cuenta                                               |
| Link                       | Link para ingresar a la cuenta                                    |
| Cantidad_Reels             | Cantidad de reels publicados por la cuenta                        |
| Reels_CompletadosComentarios | Cantidad de Reels de los cuales se ha extraído información        |

### Hoja Links_Reels
| Nombre Columna             | Descripción                                     |
|----------------------------|-------------------------------------------------|
| Link                       | Link del reel                                   |
| Descripcion                | Descripción del Reel                            |
| Vistas                     | Número de vistas del reel                       |
| Cuenta                     | Cuenta a la que pertenece el reel               |
| Cantidad Comentarios       | Número de comentarios del reel                  |
| Fecha Publicacion Video    | Fecha de publicación del reel                   |
| Cantidad de comentarios capturados | Comentarios ya capturados del reel         |
| Fecha Consulta             | Fecha de la consulta                            |

### Hoja Informacion_Reels
| Nombre Columna             | Descripción                                     |
|----------------------------|-------------------------------------------------|
| Nombre_Usuario             | Nombre del usuario                              |
| Comentario                 | Contenido del comentario                        |
| Me_Gustas                  | Cantidad de "me gusta" del comentario          |
| Link_Usuario               | Link del perfil del usuario que comentó         |
| Link_Publicacion           | Link del reel                                   |

## Proceso de desarrollo 
![7](https://github.com/Juanba2002/Proyecto_Algoritmos/assets/112012566/688ec1ef-83b9-4299-bdcb-6ec6eac29439)
![8](https://github.com/Juanba2002/Proyecto_Algoritmos/assets/112012566/f897e75e-c36f-4b42-89d1-45a9ec21a0d7)

## Cómo Usar

### Descarga e Instalación de UiPath Studio
1. Visita el sitio oficial de [UiPath](https://www.uipath.com/) y navega a la sección de descargas.
2. Selecciona la versión de UiPath Studio Open Source y descárgala.
3. Sigue las instrucciones de instalación proporcionadas por el instalador de UiPath.

### Autenticación en Google Sheets
Para permitir que nuestro proyecto interactúe con Google Sheets, es necesario configurar la autenticación:

1. Accede a la [Consola de Desarrolladores de Google](https://console.developers.google.com/) y crea un nuevo proyecto.
2. Busca y habilita la API de Google Sheets para tu proyecto.
3. Ve a la sección de credenciales, crea credenciales de tipo OAuth 2.0 y descarga el archivo JSON de configuración.
4. En UiPath, utiliza el archivo JSON de credenciales para autenticarte mediante las actividades de GSuite.

### Configuración del Navegador Edge con UiPath
Para utilizar Microsoft Edge en tus automatizaciones con UiPath, sigue estos pasos:

1. Asegúrate de tener la última versión de Microsoft Edge instalada.
2. Abre UiPath Studio y ve a `Herramientas` > `Extensiones` > `Extensiones de Navegador`.
3. Selecciona la extensión para Microsoft Edge y sigue las instrucciones para instalarla.
4. Reinicia el navegador y verifica que la extensión esté habilitada.

### Ejecución del Proceso Automatizado
Una vez configurado todo, sigue estos pasos para ejecutar tu proceso automatizado:

1. Abre el proyecto en UiPath Studio.
2. Asegúrate de que todas las configuraciones previas estén correctas y que las dependencias del proyecto estén actualizadas.
3. Haz clic en el botón `Play` para iniciar la ejecución del proceso automatizado.
4. UiPath ejecutará el proceso paso a paso, extrayendo y guardando datos en Google Sheets según lo configurado.

### Notas Adicionales
- Es posible que necesites ajustar los selectores en UiPath si las interfaces de las páginas web con las que interactúas han cambiado.
- Asegúrate de tener permisos adecuados en Google Sheets para que UiPath pueda leer y escribir en las hojas de cálculo.

