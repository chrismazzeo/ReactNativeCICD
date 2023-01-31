<!--- 
[![Build status](https://build.appcenter.ms/v0.1/apps/c1049a87-b866-48c8-868b-3ed00cbbe73d/branches/dev/badge)](https://appcenter.ms)
-->
[![Build status](https://build.appcenter.ms/v0.1/apps/afcc0dd6-e114-4480-bdee-c63a264f4a09/branches/dev/badge)](https://appcenter.ms)


Android 
1. Firma Release
	1. Crear una carpeta fuera del proyecto llamada <MyProject>_Certificate
	2. Generar en esa carpeta el Keystore desde Android Studio --> Build --> Generate Signed Bundle/APK 
	3. Actualizar keystore.properties con los valores
	3. Remover keystore.properties del repositorio (tiene que quedar solo local) y agregarlo al .gitignore
