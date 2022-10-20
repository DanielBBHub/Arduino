# Arduino  

En este repositorio encontramos el codigo en C correspondiente codificado con Arduino. El objetivo principal de este código es enviar iBeacons para posteriormente ser detectados y procesados mediante una aplicación móvil con el fin de representarse en una página web, alojada en un servidor REST. 
Este codigo cuenta con la siguiente estructura: 

Función SetUp(): en esta funcion se inicializa el puerto serie con los baudios correspondientes y se le  
asigna un nombre al iBeacon, ademas de hacer la llamada a la funcion StartAdverstising().

Función StartAdvertising(): en esta funcion se añade una flag, un txPower y un nombre, ademas de un UUID,  
un intervalo y se inicia el proceso de advertising

Función Loop(): en esta funcion se cuentan segundos 
  
Dentro de la cabecera tenemos diversa información:  
  -Nombre  
  -UUID  
  -TxPower  
  -Manufacturer  
  -Major  
  -Minor  
  -Flag
