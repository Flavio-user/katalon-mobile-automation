# Automatización Mobile con Katalon Studio - Sauce Labs Demo App

## Descripción

Proyecto de pruebas automatizadas mobile construido con **Katalon Studio** y **Appium** para validar flujos principales sobre la aplicación Android **Sauce Labs My Demo App**.

## Tecnologías y Herramientas

- **Framework de Automatización:** Katalon Studio
- **Motor Mobile:** Appium
- **Plataforma:** Android (dispositivo físico con depuración USB / ADB)
- **Aplicación bajo Prueba:** Sauce Labs My Demo App (`mda-2.3.0-27.apk`)

## Cobertura de Pruebas y Buenas Prácticas

- Inicio de la aplicación (`startApplication`) y navegación en **Sauce Labs My Demo App**.
- Flujo de inicio de sesión mediante acciones `tap` sobre elementos del `Object Repository`.
- Localización de elemento por ID (`com.saucelabs.mydemoapp.android:id/productTV`) y verificación de texto exacto (`Sauce Labs Backpack`) mediante `verifyElementText`.
- Cierre controlado de la aplicación (`closeApplication`).

## Ejemplo de Caso de Prueba

**Escenario:** Inicio de sesión y verificación de producto en Sauce Labs My Demo App (`Test Cases/Nuevo Test Case`).

1. Iniciar la aplicación Android (`startApplication`) en el dispositivo conectado.
2. Abrir el menú lateral y seleccionar la opción **Log In** (`tap`).
3. Seleccionar el usuario de prueba (`bodexample.com`) y presionar el botón **Login**.
4. Ingresar al detalle del producto y verificar mediante `verifyElementText` que el título corresponda exactamente a `Sauce Labs Backpack`.
5. Cerrar la aplicación (`closeApplication`).
6. **Resultado esperado:** Los 8 pasos se ejecutan sin errores (`Passed`) en el `Log Viewer` de Katalon Studio.

## Evidencia de Ejecución

<img width="1915" height="964" alt="Captura de pantalla 2026-11-25 163927" src="https://github.com/user-attachments/assets/1a81af7f-72a6-4cb8-b4ab-ddd61b841224" />


## Cómo Ejecutar el Proyecto

1. Conecte un dispositivo Android con depuración USB habilitada (o iniciá un emulador).
2. Abra el proyecto en Katalon Studio.
3. Abra el caso de prueba dentro de **Test Cases** (`Nuevo Test Case`) y ejecútelo seleccionando **Android** como entorno de ejecución.

## Autor

- **Flavio Matías Baldini** – QA Automation Tester
- **LinkedIn:** 
