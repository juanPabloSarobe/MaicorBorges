Cambios implementados en la rama = nuevaRama

1) se elimo restos de codigo que rompian el proyecto en los HTML (segun fotos tomadas)
2) se reestructuro la declaracion de imports en style.scss. se colocaron primero las variables luego los estilos generales.
3) se elimino los import en el resto de los scss que duplicaban el codigo en el css final.
4) se agrego comandos en el package.json, para ejecutar correctamente Sass.




Cosas Importantes para hacer
1) renombrar todas las clases de los scss. No utilizan el estandar de separar las palabras con guión ni el estandar camelCase. 
Esto es importante y te van a bajar puntos. hace al orden del codigo y ayuda cuando son mas de una persona los que trabajan en el.

ejemplo:
asi figura actualmente:
.textovidaobra {}

la forma correcta es:
.texto-vida-obra{}
o
.textoVidaObra{}

