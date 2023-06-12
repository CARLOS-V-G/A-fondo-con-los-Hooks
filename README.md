Nota: Si encuentras algún error al intentar levantar el servidor, sigue los pasos adicionales a continuación.

Borra manualmente la carpeta ``node_modules``

Ejecuta los siguientes comandos en la terminal, en orden, para reinstalar y actualizar las dependencias:

 ``npm install``
 
Este comando instalará las dependencias listadas en el archivo package.json.

```npm update```

Este comando actualizará los paquetes a las versiones más recientes permitidas por las restricciones de versión.

``npm install react-scripts@5``

Este comando instalará la versión 5 de los scripts de React necesarios para el proyecto.

Una vez completados los pasos anteriores, intenta nuevamente levantar el servidor con ``npm start``.
