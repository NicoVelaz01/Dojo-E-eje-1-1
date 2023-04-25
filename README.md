# DOJO - 1-1 

![LOGO TINKERCAD](https://github.com/iagovalverde/EjemploDocumentacion/blob/main/img/ArduinoTinkercad.jpg)

## INTEGRANTES
* Iago Valverde Pachiani
* Nicolás Velazquez
* Lucas Siguenza 
* Enzo Pose
* Victoria Rodriguez

## PROYECTO: DOJO 1-1

![IMAGEN DEL PROYECTO](https://i.im.ge/2023/04/26/L8B5ya.arduino.png)

## DESCRIPCIÓN

El proyecto es un semáforo con 2 lámparas led (de cada color). <br/>
El verde dura 5 segundos. <br/>
El amarillo dura 3 segundos. <br/>
Rojo dura 5 segundos.<br/>
Además posee señalización para personas no videntes, que suena durante la luz roja dos veces a cada segundo.

## FUNCIÓN PRINCIPAL

Estas dos funciones se encargan de encender y apagar los leds. <br/> 
led, led_dos, tiempo, tiempo_dos son parametros que pasamos a las funciones para despues asignarles el led que se prende y apaga y el tiempo, respectivamente. <br/>
Los leds son asignados a través del hashtag define a los pines a los cuales están conectados.

```C++ 
void encender(int led, int led_dos, int tiempo)
{
  digitalWrite(led, HIGH);
  digitalWrite(led_dos, HIGH);
  delay(tiempo);
}

void apagar(int led, int led_dos, int tiempo_dos)
{
  digitalWrite(led, LOW);
  digitalWrite(led_dos, LOW);
  delay(tiempo_dos);
}

```

## LINK AL PROYECTO

* [proyecto](https://www.tinkercad.com/things/dXHO8cR8pMh-nicolas-velazquez-div-1d-ej-dojo-1-1/editel?sharecode=j4ETB4vELFENN9Lw4zkdEWaWR_TfscaaLrh3dLDjOv4)