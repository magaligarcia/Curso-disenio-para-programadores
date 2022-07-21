# Curso-disenio-para-programadores

# 1. Fundamentos del diseño

## 1.1. El proceso creativo

El proceso creativo consta de algunos pasos:

1. **Preparación:** Investigar, recopilar información relativa a un problema.
2. **Incubación:** Experimentar, sintetizar, ver cómo alguien ha solucionado un problema.
3. **Iluminación:** Idear, imaginar.
4. **Evaluación:** Criticar, replantear. Definir si las  soluciones son prácticas o viables.
5. **Implementación:** Construir, trabajar.

Éste proceso se aplica a problemas de la vida cotidiana. 

## 1.2. Conceptos básicos de diseño.

### 1.2.1. Balance:

Se refiere a la estructura y estabilidad de una composición, en done la posición de cada elementos está dada por su peso visual.

El balance puede ser simétrico o asimétrico.

![image](https://user-images.githubusercontent.com/60717025/180315337-f7146ffb-f83a-4b6d-89e2-23add48b9485.png)

### 1.2.2. Contraste

El contraste se puede utilizar para utilizar para señalar un concepto marcado por la diferencia entre dos elementos. (ejemplo: claro y oscuro, grande y pequeño, antiguo y nuevo)

![image](https://user-images.githubusercontent.com/60717025/180315465-6e023a72-3a3d-4d52-bd9d-35855d8f28e1.png)

### 1.2.3. Alineación

Nos permite crear una ruta visual entre diferentes elementos que le queremos señalar al usuario.
![image](https://user-images.githubusercontent.com/60717025/180315514-8d72a379-8f2b-4174-8a51-a7a02e843dbb.png)

### 1.2.4. Proximidad

Nos permite agrupar diferentes elementos. Se pueden agrupar elementos dependiendo de varias categorías. 

![image](https://user-images.githubusercontent.com/60717025/180315563-643fbba5-8617-416f-a62c-60a28fe67b04.png)

### 1.2.5. Repetición

Es muy utilizada para generar concepto de marca (estilos repetitivos en sus interfaces)

![image](https://user-images.githubusercontent.com/60717025/180315604-44b31c58-0311-4b57-a59c-4718f5028612.png)

### 1.2.6. Espacio

Se puede aprovechar el espacio de una interfaz de muchas maneras.

## 1.3. Diseño responsivo.

Se trata de crear diferentes diseños para diferentes tamaños de pantalla. Es importante empezar por dispositivos móviles. Ésto garantiza que empecemos por los requerimientos mínimos, que separa las capas de contenido y disponibilidad. 

Es importante utilizar sistema de grillas y columnas.

- Para hacer responsive design se puede utilizar la mejora progresiva o Progresive enhancement.  Se parte de una base sólida y se van añadiendo capas de complejidad de manera progresiva.
- También existe la degradación agraciada en la que se parte de una versión completa a la que se le van removiendo capas de complejidad para garantizar su funcionamientos en todos los tamaños de pantalla y sistemas operativos.

Por ejemplo en la mejora progresiva se puede manejar el siguiente flujos:

Contenido (data) ⇒ wireframes (html) ⇒ Diseño visual (CSS) ⇒ Animaciones (css o js)

## 1.4. Accesibilidad y diseño.

> *El poder de la web está en su universalidad. El acceso de todas las personas independientemente de la discapacidad es un aspecto esencial. Tim Berners-Lee, W3C Director*
> 

Es una obligación que nuestras páginas sean visibles. 

Para lograr que la accesibilidad sea implementada es prudente realizar los siguiente:

- Utilizar HTML semántico.
- Utilizar tamaños de fuentes accesibles.
- Utilizar colores que tengan un contraste adecuado.
- Garantizar que el código de color no sea la única forma de relacionar contenido.
- Diseñar teniendo en cuenta los estados "focus" y "active" de los componentes.
- Agregar etiquetas y textos descriptivos a los campos del formulario.
- Garantizar que las animaciones no bloquean el acceso al contenido.
- Escribir contenido descriptivo que pueda reemplazar videos e imágenes.

## 1.4. El brief.

El brief es un documento en donde se consignan todos los objetivos y datos relevantes a nuestra aplicación (hoja de ruta). En este documento se tienen principalmente:

- Descripción del cliente o empresa.
- Objetivos o retos.
- Target o audiencia.
- Competencia.
- Distribución.

# 2. Diseño y experiencia de usuario (UX)

## 2.1. Definición de diseño UX.

> *Si queremos que a nuestros usuarios les guste nuestro software, debemos diseñarlo para  que se comporte como una buena persona: respetuoso, generoso y colaborador.  Alan Cooper.*
> 

El diseño UX se basa en el usuario y en la usabilidad. El diseño UX tiene diferentes etapas.

1. Investigación: Recopilar datos de como se comportan los usuarios y como manejan otras aplicaciones.
2. Análisis: Lo se que hacemos es clasificar esta información y agruparla y definir unos objetivos a nivel de usuario
3. Diseño: Crear prototipos y flujos de usuario. 
4. Pruebas de usuario: Éstas pruebas se hacen con papel y otros recursos. 

## 2.2. Diagramas de flujos.

Lo que se hace es traducir los requerimientos del brief a elementos tangibles. Por ejemplo:

Objetivo

- Dar a conocer sus productos.
- Aumentar la presencia en línea.
- Hacer pedidos online.
- Dar a conocer su marca.

Requerimientos

- Menú y promociones.

- Redes Sociales.
- Pedidos.
- Contacto y sucursales.

Se puede hace un mapa del sitio con todas la rutas posibles de la aplicación. Aquí se denotan las secciones principales, las secciones secundarias y las páginas externas. 

![image](https://user-images.githubusercontent.com/60717025/180315694-3b6fc35c-91b9-4798-83a6-0423428bfbf5.png)

Los "user flows" son todos los pasos necesarios que tiene que realizar un usuario para completar la tarea. Lo anterior nos sirve para ver cuantas pantallas o componentes debemos tener en la aplicación. 

![image](https://user-images.githubusercontent.com/60717025/180315767-a73d82ca-4725-4056-aaed-82c63d0e05cd.png)

## 2.3. Wireframes y componentes.

Un wireframe es un plano de nuestra aplicación. Se empiezan a hacer bocetos y bosquejos de todas las pantallas y componentes que tendría nuestra aplicación. Es bueno hacer los bocetos a mano con el fin de darle rienda suelta a la imaginación.

![image](https://user-images.githubusercontent.com/60717025/180315814-5d91ae84-4fa3-48d8-9528-d6fa6946e0fc.png)

Los wireframes pueden ser de baja fidelidad o de alta fidelidad. 

# 3. Diseño de interfaz de usuario (UI)

**Diseño UX**

Se enfoca en la investigación, prototipado y arquitectura de la información.

- Interacción
- Prototipado
- Arquitectura de la información
- Investigación y pruebas de usuario

**Diseño UI**

Se enfoca en crear la capa de estilos visuales que va por encima de la estructura de contenido.

- Diseño visual
- Colores
- Layouts
- Tipografía

## 3.1. Moodboard y linea gráfica.

Un moodboard es un documento o un tablero en donde se colectará información visual de estilis visuales, colores etc que podría llevar nuestra aplicación. No existe ninguna regla para crear este moodboard.

![image](https://user-images.githubusercontent.com/60717025/180315860-0df32647-4991-47d0-84ac-d3e607dabc32.png)

## 3.2. Teoría del color.

Se debe preguntar si los colores elegidos son funcionales o son adecuados para los que se quiere transmitir. 

La psicología del color es una área de estudio que se dedica a investigar la forma en la que el cerebro percibe los colores y los asocia a conceptos y sentimientos. 

- Se debe usar un código de colores consistentes.
- Exceso de color hace que los usuarios no se puedan enfocar en una acción a la vez.
- Que la paleta de color sea accesible.
- Definir una paleta de color.

## 3.3. Paletas de color.

Existe los colores primarios, secundarios y terciarios. 

- Combinación monocromática: Se usa un solo color y se le cambian los niveles de opacidad.
- Combinación análoga: Combinar un color primario uno secundario y uno terciario consecutivos.
- Combinación terciaria: Se trata de combina un color primario y uno secundario opuestos en el círculo cromático.
- Combinación triádica: Combina tres colores del circulo cromática separados equidistantes uno del otro.
- Combinación tetraédrica: Consiste en combinar cuatro colores dos primarios y dos secundarios creando un rectángulo.

[color-wheel](color.adobe.com/es/create/color-wheel)

Adobe Color

## 3.4. Tipografía.

Se hacen las siguientes recomendaciones para el uso eficiente de tipografías.

- Mantener el número de fuentes al mínimo.
- Tratar de usar fuentes estándar.
- Limitar la cantidad de texto: Las páginas web no son libros.
- Elegir tipografías que sean legibles para diferentes tamaños.
- Mantener altos de línea espaciados.
- Asegurarse de tener suficiente contraste.
- Evitar usar animaciones intermitentes.

## 3.5. Layout y sistema de grillas.

La configuración de las grillas depende del tamaño del dispositivo. Se deben configuarar los breakpoints:

- xs: 360px
- s: 440px
- m: 768px
- l: 1280px
- xl: 1440px

## 3.6. Sistemas de componentes UI.

Es bueno separa las funcionalidades por componentes (se podría crear una biblioteca visual). Unidades individuales de funcionalidad. 

## 3.7. Themas y costumización.

Se puede cambiar todos los colores dependiendo de una decisión  o acción. 

## 3.8. Imágenes para la web.

### 3.8.1. Tipos de imágenes.

- JPG: para fotografía o degradados.
- PNG: Imágenes decorativas que requieren un fondo transparente.
- SVG: Imágenes vectoriales y convertibles a código.
- Gif: Imágenes animadas pero muy pesadas.

### 3.8.2.Recomendaciones para el uso de imágenes.

- Se deben ubicar imágenes que aporten al contenido, no debe ser innecesarias.
- Las imágenes deben ser consecuentes con la paleta de color.
- Las imágenes tienen licencia.
- Las imágenes deben ser comprimidas al tamaño del contenedor final.
- Considerar estrategias como *"lazy loading"*.
- Asegurar el atributo alt a imágenes que tienen un contenido descriptivo.

## 3.9. Gráficos en movimiento para web.

### 3.9.1. Tipos de animaciones.

- **CSS Animado:** Animaciones de elementos HTML, es recomendable para animaciones sencillas.
- **SVG animado:** Animado de elementos vectoriales, se puede modificar con CSS.
- **JS(Canvas, webGL):** Indicado para animaciones complejas como animacions de datos o 3D.
- **Videos:** Indicado para filmaciones y animaciones de alta complejidad y corta duración.

### 3.9.2. Recomendaciones para el uso de animaciones.

- Una página muy animada es una página que saca rápido al usuario.
- Procurar que no se reproduzca automáticamente y que no tengan sonido.
- Que las animaciones no tengan flashes.
- Si la animación aporta al contenido, es necesario añadir transcripciones.
- Evitar que la animaciones bloqueen la lectura básica del contenido.
- Recordar que las animaciones y vídeos afectan el rendimiento de la página.
