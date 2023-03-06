En este apartado no se explicará en detalle cada línea de código de cada archivo porque puede
ser demasiado. Además, el alumnado puede buscar por internet si tiene cualquier duda para
recolectar más información al respecto.
Pero si es muy importante conocer y comprender que es cada uno de estos archivos.

**Tslint.json:** archivo de configuración (linter) donde se especifican reglas que les van a
  obligar a programar de cierta manera.

**Tsconfig.json:** archivo de configuración de typescript. Le dice a typescript como quiere
  que se traduzca a JS o como quiere que funcione en este proyecto. Es muy extraño que
  el usuario haga alguna modificación en este archivo.

**Tsconfig.spec.json:** extiende del archivo tsconfig.json y le añade funcionalidades. Está
  relacionado con la parte de las pruebas. Básicamente son pruebas unitarias o pruebas
  de integración (ya lo hemos visto en clase). Son pruebas para asegurarse que el código
  del programa funcione como se espera.

**Tsconfig.app.json:** extiende del archivo de configuración tsconfig.json y también le
  añade funcionalidades. Lo veremos más adelante.

**README.md:** Funciona a modo de texto mediante el lenguaje markdown. Para
  visualizarlo en VSC se pueden seguir los siguientes pasos: Control + Shift + p ->
  markdown -> markdown: Open Preview.

**Package.json:** Normalmente es un archivo de configuración delicado y no se deberían de hacer modificaciones. Si se quiere añadir alguna cosa, como por ejemplo un nuevo paquete, lo haremos mediante comandos. Este archivo se podría editar manualmente pero si no lo controlamos muy bien nos puede provocar algún que otro dolor de cabeza.
  En este archivo están las dependencias que utilizaremos a lo largo del curso.

**Package.lock.json:** Tampoco lo vamos a configurar manualmente pero este archivo nos dice cómo se construyen los módulos de node.

**Angular.js:** es un archivo importante para nuestra aplicación, el cual contiene configuraciones importantes para nuestra aplicación. Lo iremos viendo a lo largo de la
  unidad didáctica.

**.gitignored:** archivos que no queremos que Git le dé seguimiento en el proyecto.

**.editorconfig:** son reglas para los archivos de TS y .md, etc.

**Node_modules:** contiene todos los módulos. Dispone de paquetes de traducción, errores, errores en la consola HTML, etc.

### Archivos dentro del SRC

**App.component.html, app.component.scss, app.component.ts y app.componen.spec.ts** hacen referencia al mismo componente de la aplicación.

**App.modules.ts:** es una clase pero dispone de un decorador especial. En este archivo se importarían los módulos. Podemos decir que es un agrupador de módulos.

**Assets:** se utilizan para colocar recursos estáticos en nuestra aplicación como imágenes, sonidos o cosas que normalmente no tienen que compilarse o traducirse a JS.

**Favicon.ico:** es el icono que nos aparece en el navegador.

**Index.html:** es la página de acceso que nosotros estamos viendo.

**Main.ts:** este archivo normalmente nunca se modifica. Ayuda a decirle a Angular en el ambiente en el que está corriendo dependiendo del target que se tenga para las aplicaciones de Angular.

**Styles.scss:** archivos de estilos global de la aplicación. En este archivo escribiremos el CSS que se aplica a nivel general en toda la aplicación. A diferencia del archivo app.component.scss que solo se aplicaría a la componente HTML.