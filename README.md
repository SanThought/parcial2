# Parcial 2

El projecto presentado es en terminos generales una modificación de `https://github.com/jhonatanBaron/Taller01042025/tree/master`, ajustado a mano para satisfacer los requisitos del parcial.

Los servicios web o "apps" y sus rutas fueron editados para funcionar con las rutas `cliente/uno` y `cliente/dos`, el servicio `registro` fue ajustado en la ruta `/reporte`, que conserva la configuración de autorización: el usuario es 'admin' y la contraseña 'password'.

El sistema tambien tiene una ruta `/panel` que retorna datos en html, presenta una página básica y presenta acceso a los reportes.

la estructura consiste en un proyecto basico con treafik:

```
ejercicio-3/
├── docker-compose.yml
├── traefik.yml
├── api-registro/        # contador simple (en un archivo `server.js`)
├── cliente-app/         # app sencilla (en un archivo `server.js`)
└── panel/             # (actualmente es un mock no-funcional, a mejorar despues) index.html
```
