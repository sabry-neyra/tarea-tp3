# TP3 - Inicialización del proyecto de Node.js

Proyecto correspondiente al Trabajo Práctico N.º 3 de Diseños y Arquitecturas de Despliegues 1.

El proyecto utiliza Node.js, Express y Nodemon.

## Dependencias

### Dependencia principal

- Express: utilizado para crear el servidor web.

### Dependencia de desarrollo

- Nodemon: utilizado para reiniciar automáticamente el servidor durante el desarrollo.

## Scripts

- `npm start`: inicia el servidor con Node.js.
- `npm run dev`: inicia el servidor utilizando Nodemon.
- `npm test`: ejecuta el comando de prueba configurado.

## Comparación entre npm install y npm ci

Se realizó la prueba en una copia limpia del proyecto, eliminando la carpeta `node_modules`.

Con `npm install` se instalaron correctamente 94 paquetes.

Luego se volvió a eliminar `node_modules` y se ejecutó `npm ci`, que también instaló correctamente 94 paquetes.

La diferencia es que `npm install` puede actualizar el `package-lock.json`, mientras que `npm ci` utiliza el `package-lock.json` para realizar una instalación limpia y reproducible.