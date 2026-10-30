# APP MOVILES cupcake

Aplicación Android de pedidos de cupcakes, desarrollada con Kotlin y Jetpack Compose como práctica de Aplicaciones Móviles.

## Funciones

- Seleccionar cantidad y sabor de cupcakes.
- Elegir la fecha de retiro.
- Consultar el resumen y el precio del pedido.
- Compartir el pedido con otra aplicación.
- Navegar entre pantallas con Navigation Compose.
- Pruebas automatizadas de interfaz y navegación en `app/src/androidTest`.

## Ejecutar en un celular

1. Clonar este repositorio y abrir su carpeta raíz en Android Studio.
2. Configurar Java 21 como **Gradle JDK** y sincronizar el proyecto.
3. Activar la depuración USB del celular, conectarlo y autorizar el equipo.
4. Seleccionar la configuración **app**, elegir el celular y pulsar **Run**.

El proyecto utiliza Gradle 8.11.1, `compileSdk` 34, `targetSdk` 34 y Android 7.0 (API 24) como versión mínima. Android Studio debe tener instalada la plataforma SDK 34.

Para ejecutar las pruebas instrumentadas, abrir una clase de `app/src/androidTest` y ejecutarla con el celular seleccionado.

Compilación e instalación manual verificadas en un TECNO LE7 con Android 11.

## Referencias

Basado en los codelabs oficiales de Android Developers:

- [Cómo navegar entre pantallas con Compose](https://developer.android.com/codelabs/basic-android-kotlin-compose-navigation?hl=es-419)
- [Cómo probar la app de Cupcake](https://developer.android.com/codelabs/basic-android-kotlin-compose-test-cupcake?hl=es-419)
- [Código original de Google](https://github.com/google-developer-training/basic-android-kotlin-compose-training-cupcake)

Se conservan los avisos de copyright del código original y la licencia Apache 2.0 incluida en `LICENSE`.
