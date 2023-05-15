# ejercicio_spd_estacion_de_subte
ejercicio, desde tinkercad  simulando una mapa de destino de subte , con un ardiono, leds, display de 7 segmentos y un buzzer.

## integrantes:
franco barahona

## funcion principal:
~~~ C 
void loop()
{	
  //agrego el valor del contador en la funcion leds
  //para prender y apagar el display , los leds y para reproducir el sonido del buzzer
	leds(contador);
  //guardo el valor retornado en contador para usarlo
  //en la funcion leds
  	contador = encender_estacion(contador);
    delay(400); // Agregamos un delay de 200 milisegundos
  //controlo que el contador esta funcionando bien por consola
  	Serial.print(contador);
}
~~~

## link del proyecto 
link: https://www.tinkercad.com/things/4YvTiammpf0-brave-jaiks-kieran/editel

## imagen:
(./img/Captura de pantalla 2023-05-15 131843.png)
