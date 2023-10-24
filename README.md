<p align="left">
  <a href="https://numl.design" target="_blank" rel="noopener noreferrer">
    <img width="311" src="/images/Numl.Design_Logo.svg" alt="Logo Numl.Design">
  </a>
</p>

[![Versión NPM](https://img.shields.io/npm/v/numl.svg?style=flat)](https://www.npmjs.com/package/numl)
[![Grado de lengua: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/numldesign/numl.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/numldesign/numl/context:javascript)
![npm](https://img.shields.io/npm/dm/numl)
[![Discordia](https://img.shields.io/discord/793832892781690891?color=7389D8&label=chat%20on%20Discord&logo=Discord&logoColor=ffffff)](https://discord.gg/sHnHPnAPZj)
[![Tasa en Openbase](https://badges.openbase.io/js/rating/numl.svg)](https://openbase.io/js/numl?utm_source=embedded&utm_medium=badge&utm_campaign=rate-badge)


Numl es un lenguaje de diseño de interfaz de usuario, una biblioteca de componentes web de interfaz de usuario y un marco CSS en tiempo de ejecución para crear rápidamente interfaces que sigan su sistema de diseño 🌈
Created By Arturo Cervantes

### [STORYBOOK](https://numl.design/storybook) | [HANDBOOK](https://numl.design/handbook) | [REFERENCE](https://numl.design/reference) | [REPL](https://numl.design/repl)

## Inicio rápido

Añada el siguiente código a su página.

vía [JsDelivr](http://www.jsdelivr.com/):

```html
<script type="module" src="https://cdn.jsdelivr.net/npm/numl@1.1.2/dist/index.js"></script>
```

¡Eso es todo! Ahora puedes utilizar todos los elementos y funciones de Numl 🚀

Intenta añadir un elemento sencillo:

```html
<nu-btn>Mi botón</nu-btn>
```
See our [Handbook](https://numl.design/handbook/getting-started) for more details and other ways to install Numl.

## Introducción
* Añada un único JS-script a su página, y usted está listo para crear virtualmente cualquier interfaz usando sólo la sintaxis HTML rápidamente. Sin bundler, sin configuración, y sin frustración.
* Integrar Numl con populares JS-Frameworks. Úsalo con SSG si quieres. 
* Utilice el sistema de generación de color y estilos-a-estado para reducir las declaraciones de estilo hasta docenas de veces en comparación con CSS simple.
* Cree fácilmente su propio sistema de diseño y kit de interfaz de usuario basado en Numl. [Ejemplo] (https://cubejs-uikit.vercel.app/)
* Personaliza tus elementos a cualquier nivel: globalmente, en contexto, directamente. Utilice tokens de diseño (propiedades personalizadas) para una forma más conveniente de personalizar.
* Elimine docenas de librerías ayudantes de UI de su proyecto porque Numl puede hacerlo por sí mismo.
* Añadir sus propios elementos, atributos de estilo, comportamientos, fichas de diseño, unidades personalizadas, y más...
* Úsalo de forma gratuita. Contribuye si te gusta. 

¿Para quién es Numl?

- **Para principiantes** Utilice un sistema de diseño bien pensado con esquema oscuro automático y modo de contraste alto para el rápido desarrollo de interfaces de usuario adaptables y accesibles. Crear nuevos componentes anidando o estilizando elementos de cimentación. 
- **Para entusiastas** Personaliza el Sistema de Diseño Numl hasta el más mínimo detalle en tiempo de ejecución usando HTML. Utilice comportamientos y sistema de control para agregar interacciones simples. Agregue su framework favorito (**Vue.js**, **Angular**, **React**, **Svelte**...) para lógica compleja.
- **Para expertos** Utilice la API JavaScript para crear elementos que sigan su Sistema de Diseño en la parte superior del **Numl**. Integre Design Tokens en elementos para tener más control. Agregue sus propios elementos, estilos, comportamientos y fichas únicos.
## Another UI Framework? Why should I care?

-**All-in-one** – Numl es tanto un lenguaje de marcado para construir rápidamente interfaces receptivas como un conjunto de elementos accesibles altamente personalizables listos para usar. Por lo tanto, puede utilizar una única herramienta integral para componer y diseñar aplicaciones web. También es posible crear interacciones simples sin escribir JS.
- **Unique** – Numl se basa en una tecnología única de generación de CSS que le permite dar rienda suelta a todo el poder de CSS moderno y tomar todos los estilos bajo su control.
- **DX Focused** – Numl se centra en proporcionar la mejor experiencia posible para desarrolladores. Tiene muchos ayudantes y soluciones incorporadas para el desarrollo rutinario de la interfaz de usuario y su enfoque atómico es conveniente para el mantenimiento y refactorización.
- **Universal** – Numl está construido sobre Web Components, una moderna API web para crear elementos reutilizables de interfaz de usuario, y es compatible con la mayoría de los modernos marcos JS. Puede usarlo tal cual o crear envolturas ligeras para su framework favorito para mejorar DX, SSR y SEO.

[Más información en NUML.DESIGN] (https://numl.design/)

## Ejemplos

* [Flex playground] (https://numl.design/storybook/layouts/flex-playground)
* [Grid Playground] (https://numl.design/storybook/layouts/grid-playground)
* [Markdown Converter] (https://numl.design/storybook/converters/markdown)
* [Deslizador antes/después] (https://numl.design/storybook/complex/before-after-slider)
* [Validación del formulario de acceso] (https://numl.design/storybook/complex/login-form)
## Construido con Numl

* [Cube.js UI Kit] (https://github.com/cube-js/cubejs-ui-kit) por **Cube Dev**.
* [Numl Website] (https://numl.design) ([Repo Link] (https://github.com/numldesign/website)) - construido con **Nuxt** y **Vue.js**.
* Old Numl Landing Page ([Repo Link] (https://github.com/tenphi/numl.design)) construido con **Parcel**.
* Old Numl Storybook ([Repo Link] (https://github.com/tenphi/numl-storybook)) construido con **Vue.js** y **Webpack**.
* [Sellerscale](https://sellerscale.com) – [Project Screenshot Light](https://github.com/tenphi/nude/blob/master/images/example-app-light.png?raw=true) | [Project Screenshot Dark](https://github.com/tenphi/nude/blob/master/images/example-app-dark.png?raw=true) | [Project Screenshot Light Contrast](https://github.com/tenphi/nude/blob/master/images/example-app-light-contrast.png?raw=true) | [Project Screenshot Dark Contrast](https://github.com/tenphi/nude/blob/master/images/example-app-dark-contrast.png?raw=true)
* [Web Standards Calendar] (https://frontend-events-numl.now.sh/) por [@KatrinLuna] (https://github.com/katrinLuna) ([Repo Link] (https://github.com/katrinLuna/frontend-events-numl)).

### Soporte del navegador

Numl se prueba en las dos últimas versiones de los siguientes navegadores:

* Microsoft Edge
* Google Chrome
* Mozilla Firefox
* Apple Safari
* Apple iOS Safari
* Google Android

Las correcciones de errores críticos en versiones anteriores se abordarán en función de su gravedad e impacto.

Si necesita soporte para IE11 o pre-Chromium Edge, esta biblioteca no es para usted. Aunque los componentes web pueden (hasta cierto punto) ser polivinílicos para navegadores heredados, su soporte queda fuera del alcance de este proyecto. Si estás usando Numl en un navegador de este tipo, vas a tener un mal momento.
## Desarrollo

* `npm start` ejecutar Numl Playground.
* `npm run build` construye la librería a `dist`:
    * `dist/index.js` - ES6 módulo amigable para agitar árboles. (Exporta el objeto global `Nude`)
* `npm run dev` construye la librería, luego sigue reconstruyéndola cada vez que cambien los archivos fuente.
* `prueba de ejecución npm` pruebas de ejecución.

## local

Ejecute `npm start` para ver la página de prueba con algunos ejemplos.



## License

[MIT](LICENSE)
