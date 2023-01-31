iOS: [![Build status](https://build.appcenter.ms/v0.1/apps/e5d4a0df-2f59-4cc1-b94f-a6ef4dd37360/branches/dev/badge)](https://appcenter.ms)
Android: [![Build status](https://build.appcenter.ms/v0.1/apps/afcc0dd6-e114-4480-bdee-c63a264f4a09/branches/dev/badge)](https://appcenter.ms)


Android 
1. Firma Release
	1. Crear una carpeta fuera del proyecto llamada <MyProject>_Certificate
	2. Generar en esa carpeta el Keystore desde Android Studio --> Build --> Generate Signed Bundle/APK 
	3. Actualizar keystore.properties con los valores
	3. Remover keystore.properties del repositorio (tiene que quedar solo local) y agregarlo al .gitignore
