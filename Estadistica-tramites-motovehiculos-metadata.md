Estadística de Trámites de Motovehículos
========================================

En este conjunto de datos se detalla la cantidad de motovehículos 0km inscriptos y motovehículos transferidos, discriminados por año, mes, provincia a la que pertenece el registro seccional en el cual se inscribió el trámite. Se consideran motovehículos: ciclomotores, motocicletas, motocarro (motocargas y motofurgones), motonetas, triciclos y cuatriciclos con motor.

http://datos.jus.gob.ar/dataset/estadistica-de-tramites-de-motovehiculos

Características
---------------

-   **Fecha de Primera Publicación:** 12/07/2016

-   **Tags o Etiquetas:** inscripciones iniciales, transferencias, motovehículos, registración, 0km, trámites, registros seccionales

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional de Registros Nacionales de la Propiedad Automotor y Créditos Prendarios

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional de Registros Nacionales de la Propiedad Automotor y Créditos Prendarios

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional de Registros Nacionales de la Propiedad Automotor y Créditos Prendarios

-   **Grupo:** Sistema Registral

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Estadística de Inscripciones Iniciales de Motovehículos AAAA-MM

-   **Nombre del archivo:** estadistica-inscripciones-iniciales-motos AAAA-MM.csv

-   **Descripción del contenido:** se detalla la cantidad de motos 0km inscriptos, por año, mes y provincia

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **tipo_vehiculo (string):** tipo de vehículo inscripto (motovehículo)

-   **anio_inscripcion_inicial (int):** año de Inscripción inicial

-   **mes_inscripcion_inicial (int):** mes de Inscripción inicial

-   **provincia_inscripcion_inicial (string):** provincia donde se radicó la Inscripción inicial

-   **letra_provincia_inscripcion_inicial (string):** letra asociada a cada provincia

-   **cantidad_inscripciones_iniciales (int):** cantidad de vehículos inscriptos

### Estadística de transferencias de Motovehículos AAAA-MM

-   **Nombre del archivo:** estadistica-transferencias-motos AAAA-MM.csv

-   **Descripción del contenido:** se detalla la cantidad de motos transferidos, por año, mes y provincia

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **tipo_vehiculo (string):** tipo de vehículo transferido (motovehículo)

-   **anio_transferencia (int):** año de transferencia

-   **mes_transferencia (int):** mes de transferencia

-   **provincia_transferencia (string):** provincia donde se efectuó la transferencia

-   **letra_provincia_transferencia (string):** letra asociada a cada provincia

-   **cantidad_transferencias (int):** cantidad de vehículos transferidos

### Notas

La actividad registral de los motovehículos está regulada por el Régimen Jurídico del Automotor ([*Digesto Jurídico del Automotor*](http://www.dnrpa.gov.ar/portal_dnrpa/regimen_juridico/informacion/rja.pdf)) y el Reglamento Interno de Normas Orgánico - Funcionales y Disposiciones Modificatorias ([*Reglamento Interno de Normas Orgánico-Funcionales*](http://www.dnrpa.gov.ar/portal_dnrpa/regimen_juridico/informacion/urinof.htm)).

**Aclaración:** en las inscripciones de motovehículos del año 2006 no se poseen datos mensualizados ni discriminados por provincia, sino que se cuenta con un total anual. Para subsanar este problema, el campos mes se lo considera con valor '99' y los campos provincia y letraProvincia aparecen vacíos.