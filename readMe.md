## Que es el V8?

V8 es el motor de código abierto de alto rendimiento de JavaScript y WebAssembly de Google, escrito en C ++. Se usa en Chrome y en Node.js, entre otros.

Esta documentación está dirigida a los desarrolladores de C ++ que desean usar V8 en sus aplicaciones, así como a cualquier persona interesada en el diseño y el rendimiento de V8. Este documento le presenta a V8, mientras que la documentación restante le muestra cómo usar V8 en su código y describe algunos de sus detalles de diseño, además de proporcionar un conjunto de puntos de referencia de JavaScript para medir el rendimiento de V8.

## Hablemos del V8

V8 implementa ECMAScript y WebAssembly , y se ejecuta en Windows 7 o posterior, macOS 10.12+ y sistemas Linux que usan procesadores x64, IA-32, ARM o MIPS. V8 puede ejecutarse de forma independiente o puede integrarse en cualquier aplicación C ++.

V8 compila y ejecuta el código fuente de JavaScript, maneja la asignación de memoria para los objetos y la basura recolecta los objetos que ya no necesita. El recolector de basura preciso, generacional y preciso de V8 es una de las claves del rendimiento de V8.

JavaScript se usa comúnmente para las secuencias de comandos del lado del cliente en un navegador, por ejemplo, para manipular objetos del Modelo de objetos de documento (DOM). Sin embargo, el DOM no lo proporciona típicamente el motor de JavaScript, sino un navegador. Lo mismo ocurre con V8: Google Chrome proporciona el DOM. Sin embargo, V8 proporciona todos los tipos de datos, operadores, objetos y funciones especificados en el estándar ECMA.

V8 permite que cualquier aplicación de C ++ exponga sus propios objetos y funciones al código JavaScript. Depende de usted decidir los objetos y funciones que le gustaría exponer a JavaScript.


## Referencias

* [**V8.dev**](https://v8.dev/docs)
