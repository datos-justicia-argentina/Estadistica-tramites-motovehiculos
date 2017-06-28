Estadística de Trámites de Motovehículos
========================================

En este conjunto de datos se detalla la cantidad de motovehículos 0km inscriptos y motovehículos transferidos, discriminados por año, mes, provincia a la que pertenece el registro seccional en el cual se inscribió el trámite. Se consideran motovehículos: ciclomotores, motocicletas, motocarro (motocargas y motofurgones), motonetas, triciclos y cuatriciclos con motor.

-   **Fecha de Publicación:** 12/07/2016

-   **Tags o Etiquetas:** inscripciones iniciales, transferencias, motovehículos, registración, 0km, trámites, registros seccionales

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional de Registros Nacionales de la Propiedad Automotor y Créditos Prendarios

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional de Registros Nacionales de la Propiedad Automotor y Créditos Prendarios

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional de Registros Nacionales de la Propiedad Automotor y Créditos Prendarios

-   **Grupo:** Sistema Registral

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Estadística de Inscripciones Iniciales de Motovehículos

-   **Nombre del archivo:** estadistica-inscripciones-iniciales-motos.csv

-   **Descripción del contenido:** cantidad de motos 0km inscriptos, por año, mes y provincia

-   **Formato:** CSV delimitado por coma, codificado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **tipo\_vehiculo (string):** tipo de vehículo inscripto (motovehículo)

-   **anio\_inscripcion\_inicial (int):** año de Inscripción inicial

-   **mes\_inscripcion\_inicial (int):** mes de Inscripción inicial

-   **provincia\_inscripcion\_inicial (string):** provincia donde se radicó la Inscripción inicial

-   **letra\_provincia\_inscripcion\_inicial (string):** letra asociada a cada provincia

-   **cantidad\_inscripciones\_iniciales (int):** cantidad de vehículos inscriptos

### Estadística de transferencias de Motovehículos

-   **Nombre del archivo:** estadistica-transferencias-motos.csv

-   **Descripción del contenido:** cantidad de motos transferidos, por año, mes y provincia

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

<!-- -->

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **tipo\_vehiculo (string):** tipo de vehículo transferido (motovehículo)

-   **anio\_transferencia (int):** año de transferencia

-   **mes\_transferencia (int):** mes de transferencia

-   **provincia\_transferencia (string):** provincia donde se efectuó la transferencia

-   **letra\_provincia\_transferencia (string):** letra asociada a cada provincia

-   **cantidad\_transferencias (int):** cantidad de vehículos transferidos

### Notas

La actividad registral de los motovehículos está regulada por el Régimen Jurídico del Automotor ([*Digesto Jurídico del Automotor*](http://www.dnrpa.gov.ar/portal_dnrpa/regimen_juridico/informacion/rja.pdf)) y el Reglamento Interno de Normas Orgánico - Funcionales y Disposiciones Modificatorias ([*Reglamento Interno de Normas Orgánico-Funcionales*](http://www.dnrpa.gov.ar/portal_dnrpa/regimen_juridico/informacion/urinof.htm)).

**Aclaración:** en las inscripciones de motovehículos del año 2006 no se poseen datos mensualizados ni discriminados por provincia, sino que se cuenta con un total anual. Para subsanar este problema, el campos mes se lo considera con valor '99' y los campos provincia y letraProvincia aparecen vacíos.
