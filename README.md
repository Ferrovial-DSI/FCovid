# FCovid
![PowerApps FCovid Tool](https://github.com/Ferrovial/FCovid/blob/main/Logo-Covid-blancoA.jpg)

El objetivo de esta app es facilitar la vuelta al trabajo en nuestras organizaciones y llevar un adecuado control de los contactos mantenidos en el ámbito laboral

# Funcionalidad

La App genera un código QR único para cada usuario de la misma, con objeto de facilitar el registro de contactos entre sus usuarios.

Dispone de las siguientes opciones de menú:

• Escanear QR, permite escanear códigos QR de otros usuarios, para registrar el haber estado en contacto con ellos.

• Buscar por Nombre, lo mismo que lo anterior pero en lugar de escanear código QR se darían de alta manualmente las personas con las que se ha tenido contacto.

• Mis Registros, consulta de las personas que hemos informado mediante las dos opciones anteriores.

• ¿Necesitas ayuda?, permite dar de alta incidencias o sugerencias

• Cláusula de Protección de Datos, para aprobación y consulta por parte de los usuarios de la App.

# Instalación

Para instalar esta app deberás descargar el fichero "Fcovid_1_0_0_1_managed.zip" e importarla como solución en un entorno de PowerApps que incluya CDS.

Una vez instalada la solución, deberás modificar el flujo "getGDPR plantilla" para indicar un site de Sharepoint y un fichero en formato pdf que contenga las claúsulas de protección de datos que deseemos incorporar. Estas claúsulas son mostradas siempre en el primer acceso de cada usuario.

![PowerApps FCovid getGDPR](https://github.com/Ferrovial/FCovid/blob/main/getGDPR.jpg)


A continuación deberemos modificar la propiedad "OnVisible" para la pantalla Ayuda para indicar la dirección de correo que queramos que reciba las incidencias o sugerencias reportadas por los usuarios desde la propia app

![PowerApps FCovid Ayuda](https://github.com/Ferrovial/FCovid/blob/main/PantallaAyuda.jpg)


# Disclaimer
Esta aplicación puede ser descargada, modificada, utilizada y/o distribuida sin más restricción que la de no ser usada para fines comerciales. La aplicación se facilita "as-is" sin soporte sobre la misma por parte de Ferrovial.
El único objetivo que pretendemos con la publicación de la misma es poder ayudar a otras compañías o asociaciones a tener un mayor control de los posibles contactos dentro del ámbito laboral.
