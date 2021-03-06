# Departamentos y Municipios de El Salvador

Departamentos y municipios de El Salvador en formato json.

Esta información puede ser consumida desde la siguiente ruta:
https://api.npoint.io/253f0ee259ef1620a547/departamentos

## Estado
- Aun se encuentra en desarrollo.
- Pendientes los datos de San Miguel, Morazán y La Unión.

### El archivo tiene la siguiente estructura:

| Propiedad |Tipo | Descripción |
| :------------- |:----------- |:---------- |
| id | string |Identificador único para cada departamento |
| nombre | string | Nombre del departamento |
| cabecera | string | Nombre de la cabecera del departamento|
|ISO3166-2| string |Código  ISO3166-2 del departamento|
| extension| number | Extensión territorial del departamento en kilómetros cuadrados|
| municipios| array |Nombres de los municipios del departamento con información especifica del municipio|


Los municipios contienen la siguiente información:

| Propiedad | Tipo | Descripción |
| :------------- | :----------| :---------- |
| id_mun| string |Identificador único del municipio|
| nombre| string |Nombre del municipio|
| cantones| number |Cantidad de cantones del municipio|
| cod_postal| string |Código postal del municipio|



## Ejemplo para accesar a la información desde Javascript:    
    
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
