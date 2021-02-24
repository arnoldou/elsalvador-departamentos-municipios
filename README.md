# elsalvador-departamentos-municipios
Departamentos y municipios de El Salvador en formato json.

Esta información puede ser consumida desde la siguiente ruta:
https://api.npoint.io/253f0ee259ef1620a547/departamentos

## Ejemplo:

fetch('https://api.npoint.io/253f0ee259ef1620a547/departamentos')
.then(response => response.json())
.then(data => console.log(data))

## NOTA:

El valor de la propiedad extension es en kilometros cuadrados.

## Referencias

Codigos Postales de los municipios

https://www.correos.gob.sv/codigos-postales

Para otros datos:

http://biblioteca.utec.edu.sv/siab/virtual/PNUD/84202.pdf
