# elsalvador-departamentos-municipios
Departamentos y municipios de El Salvador en formato json.

Esta información puede ser consumida desde la siguiente ruta:
https://api.npoint.io/253f0ee259ef1620a547/departamentos

### El archivo contiene la siguiente información:

* id - Identificador único para cada departamento
* nombre - Nombre del departamento
* cabecera - Nombre de la cabecera del departamento
* ISO3166-2 - Código  ISO3166-2 del departamento
* extension - Extensión territorial del departamento en kilómetros cuadrados
* municipios - Nombres de los municipios del departamento con información especifica del municipio

Los municipios contienen la siguiente información:

* id_mun - Identificador único del municipio
* nombre - Nombre del municipio
* cantones - Cantidad de cantones del municipio
* cod_postal - Código postal del municipio


## Ejemplo:

fetch('https://api.npoint.io/253f0ee259ef1620a547/departamentos')
.then(response => response.json())
.then(data => console.log(data))

## Referencias

Codigos Postales de los municipios

https://www.correos.gob.sv/codigos-postales

Para otros datos:

http://biblioteca.utec.edu.sv/siab/virtual/PNUD/84202.pdf

## About me

Arnoldo Umaña

### Miembro de la Comunidad NodeSchool San Miguel

https://nodeschoolsm.io/

https://github.com/nodeschool/sanmiguel
