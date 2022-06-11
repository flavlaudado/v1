# v1
POV RGB, versión 1.
Varita de 8 LEDs RGB <3

Proyecto para realizar persistencia de la visión (POV) con una placa a medida con 8 LEDs RGB controlados con Arduino Nano.

Funcionamiento
Una hilera de luces de LED se encienden y apagan a alta frecuencia en base a secuencias de bytes enviadas por un microcontrolador (Arduino) encargado de controlar dicha rutina. Al mover el dispositivo con rapidez o al ser capturado con una cámara, utilizando larga exposición, se pueden percibir imágenes y textos.

Software
En esta primer versión controlamos los LEDs con un programa desarrollado en Arduino para mandar texto y dibujos pre-diseñados. Los colores RGB se controlan mediante transistores y toda la hilera usa el mismo color por cada momento.
Hay un programa desarrollado en Processing con la posibilidad de poder dibujar y crear nuevos diseños o incluso una nueva fuente tipográfica. Las posibilidades de este software son para crear dibujos del tamaño de los caracteres (7 filas x 8 columnas). Este programa requiere instalar la librería ControlP5.

Hardware
Incorporamos el diseño de placa doble faz. Que utiliza un arduino Nano, 8 LEDs RGB ánodo común, 3 transistores NPN, 24 resistencias 220Ω, 3 resistencias 1KΩ, switch y un clip de batería.

![alt text](https://github.com/povrgb/v1/blob/main/Software/img/placa_povrgb.JPG)

Beca FNA
El proyecto contó con la beca Formación del Fondo nacional de las artes para su desarrollo y el dictado de un taller gratuito en Mayo-Junio de 2022 donde cada participante soldó y aprendió a programar su propia placa.

![alt text](https://github.com/povrgb/v1/blob/main/Software/img/flyerCuadrado.png)

Registro y pruebas

![alt text](https://github.com/povrgb/v1/blob/main/Software/img/pruebas0.JPG)
