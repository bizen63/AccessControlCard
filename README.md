# AccessControlCard
Sistema de identificación de acceso mediante lector RFID de 125 Khz con display (16x2) I2C.
El conexionado de los circuitos se deduce del mismo código.
En primer lugar, una vez conexionados los circuitos, utilizaremos el programa llamado RFID_READ_CARD.ino para leer el código de nuestras tarjetas.
En segundo lugar cargaremos en nuestro IDE arduino el programa CONTROL_ACCESO_LCD_I2C.ino y modificaremos el código de nuestras tarjetas con los resultados obtenidos en el paso anterior y los nombres del ejemplo con los que deseemos.
Finalmente subiremos el programa CONTROL_ACCESO_LCD_I2C.ino modificado y ya podemos utilizar el sistema de acceso.
Ahora queda al criterio de cada uno incrementar el sistema con nuevas posibilidades.
