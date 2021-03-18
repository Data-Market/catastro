# Datasets de Catastro

<a href="https://datamarket.es">
  <img src="https://datamarket.es/media/banners/catastro-banner.png">
</a>

## Descripción

__Todas las propiedades de España con sus características__. Incluyendo muchas que no vienen en la información oficial del catastro, como si la propiedad tiene jardín, piscina, ascensor, portero físico, parking, trastero, etc.

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: actualizado cada 3 meses
* __Volumen estimado__: 25 millones de registros
* __Histórico__: desde septiembre de 2020

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#catastro-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/catastro/blob/main/catastro-enriquecido-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

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
