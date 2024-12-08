Segundo documento LMI
=
Identificación de los espacios de nombres en documentos (AndroidManifest.xml)
-
<br> <br>
En un documento Android, como el AndroidManifest.xml, los espacios de nombres (namespaces) se utilizan para definir contextos para los atributos i elementos XML, asegurandose que estos no entran en conflicto con otras definiciones o bibliotecas.

* ***xmlns:***
    + Es el espacio de nombres principal para todos los atributos estándar de Android.
    + Se utiliza para atributos específicos de Android, como ```android:icon```, ```android:label```, ```android:theme```, etc.
    + Espacio de nombres usado para atributos que solo se aplican en tiempo de desarrollo. Proporciona instrucciones o modificaciones para herramientas como Android Studio sin afectar el comportamiento final de la aplicación.
    + Se utilizan para referenciar espacios de nombres de otras bibliotecas o componentes específicos de la aplicación, como bibliotecas externas de Jetpack, Material Design, etc.
    