# Evidencia TP3

## Instalación en copia limpia

Se realizó una copia limpia del proyecto y se eliminó la carpeta `node_modules`.

### npm ci

Se ejecutó:

`npm ci`

Resultado:
- 94 paquetes instalados.
- 95 paquetes auditados.
- 0 vulnerabilidades encontradas.

### npm install

Se eliminó nuevamente `node_modules` y se ejecutó:

`npm install`

Resultado:
- 94 paquetes instalados.
- 95 paquetes auditados.
- 0 vulnerabilidades encontradas.

## Diferencia práctica

`npm install` instala las dependencias según `package.json` y puede actualizar `package-lock.json` cuando corresponde.

`npm ci` realiza una instalación limpia utilizando `package-lock.json`, buscando que las versiones instaladas sean reproducibles.

## Scripts funcionales

- `npm test` → muestra `No tests yet`.
- `npm start` → inicia correctamente el servidor.
- `npm run dev` → inicia correctamente el servidor utilizando Nodemon.
