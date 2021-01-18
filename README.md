# Catastro

Todas las propiedades de España con sus características. Incluyendo muchas que no vienen en la información oficial del catastro, como si la propiedad tiene jardín, piscina, ascensor, portero físico, parking, trastero, etc. Este dataset se puede adquirir en [Data Market](https://datamarket.es/#catastro-dataset), plataforma de referencia de datos externos en España. Puede consultar nuestro catálogo de datos en la siguiente url: [datamarket.es](https://datamarket.es/)

A continuación se muestran las columnas de las que consta el dataset en el formato __nombre_columna__: __ejemplo_columna__, donde ejemplo_columna representa posibles valores que se pueden encontrar en dicha columna.

| nombre              | tipo | descripción                                                                 | ejemplo              |
|---------------------|------|-----------------------------------------------------------------------------|----------------------|
| province            | str  | Provincia donde está ubicado el inmueble.                                   | Guadalajara          |
| town                | str  | Ciudad donde está ubicado el inmueble.                                      | Guadalajara          |
| street              | str  | Calle donde está ubicado el inmueble.                                       | Calle Mayor          |
| number              | str  | Número de la calle donde está ubicado el inmueble.                          | 34                   |
| name                | str  | Nombre descriptivo del inmueble.                                            | Esc.E 1º DR          |
| area                | int  | Superficie en m² de los que consta el inmueble.                             | 56                   |
| is_residential      | bool | Indica si se trata de una vivienda (False significa que no es residencial). | True                 |
| reference           | str  | Referencia catastral.                                                       | 6180804VK8968S0004IY |
| postal_code         | int  | Código postal del inmueble.                                                 | 19001                |
| latitude            | geo  | Latitud en la que se encuentra el inmueble.                                 | 40.631345746         |
| longitude           | geo  | Longitud en la que se encuentra el inmueble.                                | -3.16518128          |
| year_built          | int  | Año de construcción del edificio.                                           | 1930                 |
| total_floors        | int  | Número de plantas del edificio.                                             | 5                    |
| neighbors_per_floor | int  | Número de vecinos por planta.                                               | 1                    |
| has_parking         | bool | Indica si el edificio tiene parking.                                        | False                |
| has_swimming_pool   | bool | Indica si el edificio tiene piscina.                                        | False                |
| has_garden          | bool | Si el edificio tiene jardín.                                                | False                |
| has_lift            | bool | Indica si el edificio tiene ascensor.                                       | False                |
| has_doorman         | bool | Indica si el edificio tiene portero.                                        | False                |
| has_storage         | bool | Indica si el inmueble tiene trastero.                                       | True                 |
