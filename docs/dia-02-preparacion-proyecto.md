# Día 2: Preparación del proyecto

## Qué he hecho

- He inicializado el proyecto Node.js.
- He instalado Express.
- He configurado TypeScript.
- He creado la carpeta src.
- He creado el archivo src/server.ts.
- He arrancado el servidor en local.
- He probado la respuesta desde navegador o Thunder Client.

## Comando para arrancar el proyecto

```bash
npm run dev
```

## URL de prueba

```text
http://localhost:3000
```

## Respuesta obtenida

```json
{
  "message": "UserManager API"
}
```

## Explicación personal


* **¿Qué hace el archivo `src/server.ts`?** Es el punto de entrada de la aplicación.

* **¿Qué hace `app.listen`?** Su función es poner la aplicación en un estado de "escucha", lo que permite que el servidor permanezca activo y atento a las peticiones HTTP que lleguen.

* **¿Qué hace `app.get`?** Se utiliza para crear una ruta o endpoint que responde específicamente al método HTTP GET.

* **¿Por qué usamos `express.json`?** Permite que la API lea e interprete datos en formato JSON enviados en el cuerpo (body) de las peticiones
.
