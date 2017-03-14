# Fiscal Data Package demo para el municipio de Madrid

Este repositorio muestra los presupuestos municipales de Madrid publicados en el formato [Fiscal Data package](http://specs.frictionlessdata.io/fiscal-data-package/#table-of-contents).

El formato Fiscal Data package es un formato abierto definido por la [OKFN](http://okfn.org/) para ayudar a gobiernos y organizaciones a publicar los datos de los presupuestos de forma sencilla y reutilizable.

Se trata de un formato en evolución constante, la versión actual de la especificación es la 0.3.0.

El ejemplo contiene dos paquetes de datos:

- `madrid-expenditure-proposed`: Presupuesto de gastos planeados para Madrid, de los años 2010 a 2016 (clasificación funcional)
- `madrid-revenue-proposed`: Presupuesto de ingresos planeados para Madrid, de los años 2010 a 2016 (clasificación económica)

Cada paquete de datos contiene un fichero `JSON` con la metainformación del paquete, definida en la especificación y destinada a los reutilizadoes, y un fichero CSV con los datos.

La especificaciǿn es lo bastante flexible como para permitir definir los datos de una forma totalmente libre. Nosotros hemos propuesto este formato, pero se podrían hacer ficheros más graduales, por ejemplo separados por años o por periodos más cortos, como trimestres.

## Acerca de

Este ejemplo ha sido creado para el Grupo de Datos Abiertos de la [FEMP](http://www.femp.es)

## Contacto

- Fernando Blat <fernando@populate.tools>
- [Gobierto](https://gobierto.es)
