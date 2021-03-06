![](./images/logos_feder.png)

# Métricas FAIR

La evaluación de indicadores de realiza de forma individual y se agrupa por áreas FAIR (FINDABLE, ACCESIBLE, INTEROPERABLE y REUSABLE).

El resultado de la evaluación por indicadores individuales se muestra a continuación:

![](./images/evaluacion_indicadores.png)

El resultado de la evaluación por áreas sería el siguiente:

![](./images/evaluacion_areas.png)

De forma general, la conclusión de la evaluación FAIR es bastante positiva, dado que por la naturaleza del proyecto ASIO, la mayoría de indicadores se cumplen de-facto, por el uso de tecnologías de linked data 5 estrellas (OWL, SKOS, HTTP, RDF, etc).

Sólo en algunos casos, dado que el proyecto aún se encuenta en un estado parcial, algunos indicadores no se cumplen por falta de referencias explicitas a recursos externos, pero que se espera queden cubiertos sin gran complejidad para el hito 2.

En los siguientes apartados se detalla la evaluación de cada uno de los indicadores.

## FINDABLE

A continuación se describen los criterios de evaluación y resultados de los 7 indicadores FINDABLE, todos ellos de prioridad *essential*. 

Todos los criterios se cumplen, por lo que la evaluación de este área sería de nivel 5

### RDA-F1-01M - Metadata is identified by a persistent identifier

**Equivalencia FAIR**: F1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Todos los datos y metadatos están identificados mediante URIs PURL ([http://purl.org](http://purl.org))

### RDA-F1-01D - Data is identified by a persistent identifier

**Equivalencia FAIR**: F1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Todos los datos y metadatos están identificados mediante URIs PURL ([http://purl.org](http://purl.org))

### RDA-F1-02M - Metadata is identified by a globally unique identifier

**Equivalencia FAIR**: F1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Todos los datos y metadatos están identificados mediante URIs PURL ([http://purl.org](http://purl.org))

### RDA-F1-02D - Data is identified by a globally unique identifier

**Equivalencia FAIR**: F1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Todos los datos y metadatos están identificados mediante URIs PURL ([http://purl.org](http://purl.org))

### RDA-F2-01M - Rich metadata is provided to allow discovery

**Equivalencia FAIR**: F2

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Se proveen metadatos tanto a nivel de ontología como de los datos importados (OWL/SKOS, Wikibase, Trellis y Memento).

### RDA-F3-01M - Metadata includes the identifier for the data

**Equivalencia FAIR**: F3

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los metadatos incluyen referencias expícitas a los datos que describen.

### RDA-F4-01M - Metadata is offered in such a way that it can be harvested and indexed

**Equivalencia FAIR**: F4

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### ACCESIBLE

A continuación se describen los criterios de evaluación y resultados de los 12 indicadores ACCESIBLE, de los cuales son 8 *essential*, 3 *important* y 1 *useful*. 

Se cumplen todos menos 1 indicador de tipo *important*, por lo que la evaluación de este área sería de nivel 3, la cual aumentaría a nivel 5 a la finalización del hito 2, tras resolver dicho indicador.

### RDA-A1-01M - Metadata contains information to enable the user to get access to the data

**Equivalencia FAIR**: A1

**Prioridad RDA**: Important

**Evaluación**: 2 – under consideration or in planning phase

Actualmente no se describe a nivel de metadatos el mecanismo de autenticación y autorización para poder tener acceso a los datos, si bien está previsto incluirlo a corto plazo.

### RDA-A1-02M - Metadata can be accessed manually (i.e. with human intervention)

**Equivalencia FAIR**: A1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### RDA-A1-02D - Data can be accessed manually (i.e. with human intervention)

**Equivalencia FAIR**: A1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### RDA-A1-03M - Metadata identifier resolves to a metadata record

**Equivalencia FAIR**: A1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### RDA-A1-03D - Data identifier resolves to a digital object

**Equivalencia FAIR**: A1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### RDA-A1-04M - Metadata is accessed through standardised protocol

**Equivalencia FAIR**: A1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### RDA-A1-04D - Data is accessible through standardised protocol

**Equivalencia FAIR**: A1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### RDA-A1-05D - Data can be accessed automatically (i.e. by a computer program)

**Equivalencia FAIR**: A1

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### RDA-A1.1-01M - Metadata is accessible through a free access protocol

**Equivalencia FAIR**: A1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### RDA-A1.1-01D - Data is accessible through a free access protocol

**Equivalencia FAIR**: A1

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### RDA-A1.2-02D - Data is accessible through an access protocol that supports authentication and authorisation

**Equivalencia FAIR**: A1

**Prioridad RDA**: Useful

**Evaluación**: 4 – fully implemented

Los datos y metadatos están publicados mediante un grafo linked data 5 estrellas (HTTP/LDP).

### RDA-A2-01M - Metadata is guaranteed to remain available after data is no longer available

**Equivalencia FAIR**: A2

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

La combinación de Trellis y Memento permite llevar un registro histórico de modificaciones que garantiza que los metadatos pervivan más allá del ciclo de vida del dato asociado.

## INTEROPERABLE

A continuación se describen los criterios de evaluación y resultados de los 12 indicadores INTEROPERABLE, de los cuales son 7 *important*, 5 *useful* y ninguno *essential*.

Se cumplen todos menos 1 indicador de tipo *important* y 3 *useful*, por lo que la evaluación de este área sería de nivel 3, la cual aumentaría a nivel 5 a la finalización del hito 2, tras resolver dichos indicadores.

### RDA-I1-01M - Metadata uses knowledge representation expressed in standardised format

**Equivalencia FAIR**: I1

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Los datos y metadatos están expresado mediante tecnología linked data (OWL, SKOS, DC, RDF, etc).

### RDA-I1-01D - Data uses knowledge representation expressed in standardised format

**Equivalencia FAIR**: I1

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Los datos y metadatos están expresado mediante tecnología linked data (OWL, SKOS, DC, RDF, etc).

### RDA-I1-02M - Metadata uses machine-understandable knowledge representation

**Equivalencia FAIR**: I1

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Los datos y metadatos están expresado mediante tecnología linked data (OWL, SKOS, DC, RDF, etc).

### RDA-I1-02D - Data uses machine-understandable knowledge representation

**Equivalencia FAIR**: I1

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Los datos y metadatos están expresado mediante tecnología linked data (OWL, SKOS, DC, RDF, etc).

### RDA-I2-01M - Metadata uses FAIR-compliant vocabularies

**Equivalencia FAIR**: I2

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Los datos y metadatos están expresado mediante tecnología linked data (OWL, SKOS, DC, RDF, etc).

### RDA-I2-01D - Data uses FAIR-compliant vocabularies

**Equivalencia FAIR**: I2

**Prioridad RDA**: Useful

**Evaluación**: 4 – fully implemented

Los datos y metadatos están expresado mediante tecnología linked data (OWL, SKOS, DC, RDF, etc).

### RDA-I3-01M - Metadata includes references to other metadata

**Equivalencia FAIR**: I3

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

La ontología referencia otras ontologías, como por ejemplo [PROV-O](https://www.w3.org/TR/prov-o/).

### RDA-I3-01D - Data includes references to other data

**Equivalencia FAIR**: I3

**Prioridad RDA**: Useful

**Evaluación**: 4 – fully implemented

Se referencian datos externos, como por ejemplo el uso de DOIs para enlazar documentos y artículos de investigación.

### RDA-I3-02M - Metadata includes references to other data

**Equivalencia FAIR**: I3

**Prioridad RDA**: Useful

**Evaluación**: 2 – under consideration or in planning phase

*This indicator is about the way metadata is connected to other data, for example linking to previous or related research data that provides additional context to the data. Please note that this is not about the link from the metadata to the data it describes; that link is considered in principle F3 and in indicator RDA-F3-01M.*

### RDA-I3-02D - Data includes qualified references to other data

**Equivalencia FAIR**: I3

**Prioridad RDA**: Useful

**Evaluación**: 2 – under consideration or in planning phase

*This  indicator is about the way data is connected to other data. The references  need to be qualified which means that the relationship role of the related  resource is specified, for example that a particular link is a specification  of a unit of measurement, or the identification of the sensor with which the  measurement was done.*

### RDA-I3-02M - Metadata includes qualified references to other metadata

**Equivalencia FAIR**: I3

**Prioridad RDA**: Important

**Evaluación**: 2 – under consideration or in planning phase

*This  indicator is about the way metadata is connected to other metadata, for  example to descriptions of related resources that provide additional context  to the data. The references need to be qualified which means that the  relationship of the related resource is specified, for example person Y is  the author of dataset X.*

### RDA-I3-04M - Metadata include qualified references to other data

**Equivalencia FAIR**: I3

**Prioridad RDA**: Useful

**Evaluación**: 2 – under consideration or in planning phase

*This  indicator is about the way metadata is connected to other data. The  references need to be qualified which means that the relationship role of the  related resource is specified, for example dataset X is derived from dataset  Y.*

## REUSABLE

A continuación se describen los criterios de evaluación y resultados de los 10 indicadores REUSABLE, de los cuales son 5 *essential*, 4 *important y 1 useful*.

Se cumplen todos menos 1 indicador de tipo *essential*, por lo que la evaluación de este área sería de nivel 0, la cual aumentaría a nivel 5 a la finalización del hito 2, tras resolver dicho indicador.

### RDA-R1-01M - Plurality of accurate and relevant attributes are provided to allow reuse

**Equivalencia FAIR**: R1

**Prioridad RDA**: Essential

**Evaluación**: 2 – under consideration or in planning phase

*The  indicator concerns the quantity but also the quality of metadata provided in  order to enhance data reusability. This indicator can be evaluated with the  help of standards registries such as the RDA-endorsed [FAIR Sharing](https://fairsharing.org/standards/?q=/format&selected_facets=type_exact:reporting%20guideline).*

Se prevé cumplir este indicador mediante el mapeo de las áreas científicas y temáticas de la UNESCO que tiene publicadas la Universidad de Murcia (hito 2).

### RDA-R1.1-01M - Metadata includes information about the licence under which the data can be reused

**Equivalencia FAIR**: R1

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Uso de licencia [Creative Commons](https://creativecommons.org/publicdomain/zero/1.0/).

### RDA-R1.1-02M - Metadata refers to a standard reuse licence

**Equivalencia FAIR**: R1

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Uso de licencia [Creative Commons](https://creativecommons.org/publicdomain/zero/1.0/).

### RDA-R1.1-03M - Metadata refers to a machine-understandable reuse licence

**Equivalencia FAIR**: R1

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Uso de licencia [Creative Commons](https://creativecommons.org/publicdomain/zero/1.0/).

### RDA-R1.2-01M - Metadata includes provenance information according to community-specific standards

**Equivalencia FAIR**: R2

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Uso de [PROV-O](https://www.w3.org/TR/prov-o/).

### RDA-R1.2-02M - Metadata includes provenance information according to a cross-community language

**Equivalencia FAIR**: R2

**Prioridad RDA**: Useful

**Evaluación**: 4 – fully implemented

Uso de [PROV-O](https://www.w3.org/TR/prov-o/).

### RDA-R1.3-01M - Metadata complies with a community standard

**Equivalencia FAIR**: R3

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están expresado mediante tecnología linked data (OWL, SKOS, DC, RDF, etc).

### RDA-R1.3-01D - Data complies with a community standard

**Equivalencia FAIR**: R3

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están expresado mediante tecnología linked data (OWL, SKOS, DC, RDF, etc).

### RDA-R1.3-02M - Metadata is expressed in compliance with a machine-understandable community standard

**Equivalencia FAIR**: R3

**Prioridad RDA**: Essential

**Evaluación**: 4 – fully implemented

Los datos y metadatos están expresado mediante tecnología linked data (OWL, SKOS, DC, RDF, etc).

### RDA-R1.3-02D - Data is expressed in compliance with a machine-understandable community standard

**Equivalencia FAIR**: R3

**Prioridad RDA**: Important

**Evaluación**: 4 – fully implemented

Los datos y metadatos están expresado mediante tecnología linked data (OWL, SKOS, DC, RDF, etc).
