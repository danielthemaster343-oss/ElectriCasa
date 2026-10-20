# ElectriCasa Android — v0.6

Aplicación educativa para dibujar instalaciones residenciales y explorar circuitos de forma visual.

## Incluye
- Plano editable 2D.
- Componentes de focos, apagadores, contactos, tablero y registros.
- Cableado visual de fase, neutro y tierra.
- Simulación didáctica de apagadores, pastillas y fallas.
- Diagnóstico visual, estimación aproximada de carga y corriente.
- Guardado local, importación/exportación de respaldos y reporte imprimible.

## Abrir y compilar
1. Instala Android Studio en una computadora.
2. Descomprime este ZIP.
3. En Android Studio elige **Open** y selecciona la carpeta `ElectriCasa_Android_Completo`.
4. Permite que Gradle descargue las herramientas solicitadas y espera a que termine la sincronización.
5. Conecta un teléfono Android con depuración USB habilitada o inicia un emulador.
6. Para probar: pulsa **Run**.
7. Para generar APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**. El APK de depuración suele aparecer en `app/build/outputs/apk/debug/app-debug.apk`.

## Estado importante
Este paquete contiene el proyecto fuente Android, no un APK compilado. El entorno donde se preparó no dispone del Android SDK ni de Gradle, así que la compilación no se ha ejecutado aquí.

## Aviso de seguridad
ElectriCasa es un simulador educativo. Sus recorridos de cables son visuales y no verifican continuidad real, terminales, calibre de conductor, caída de tensión, selectividad de protecciones ni cumplimiento normativo. No usar para construir o energizar una instalación real sin revisión de una persona electricista calificada.
