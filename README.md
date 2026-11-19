# Automatización Mobile con Katalon Studio - Sauce Labs Demo App

Proyecto de pruebas automatizadas mobile construido con **Katalon Studio** y **Appium** para validar flujos principales en Android.

## Qué cubre este proyecto
- Inicio de la aplicación y navegación en **Sauce Labs My Demo App**.
- Flujo de inicio de sesión.
- Localización de elemento por **ID** (`com.saucelabs.mydemoapp.android:id/productTV`) y verificación de texto exacto (`Sauce Labs Backpack`) mediante `Mobile.verifyElementText`.

## Tecnologías utilizadas
- Katalon Studio
- Appium
- Android (dispositivo físico con depuración USB / ADB)

## Cómo ejecutarlo
1. Conecte un dispositivo Android con depuración USB habilitada (o inicie un emulador).
2. Abra el proyecto en **Katalon Studio**.
3. Abra el caso de prueba dentro de `Test Cases` y ejecútelo con el dispositivo conectado.
