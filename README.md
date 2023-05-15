# Proyecto Fase 2

## Descripcion

El objetivo principal de este proyecto es que el estudiante pueda dar una solución en base a la implementación de un sistema de análisis y reportes para que la empresa solicitante llegue a tener un control sólido sobre sus ventas y de igual forma de sus
inventarios.

## Flujo de datos

![Flujo de datos](/Flujo.png)

## Reportes

Nota: tomar en cuenta los siguientes significados, al momento de ser mencionados en los reportes:

* Top = los primeros 5.
* item1 -> item2 -> item3 = refiere a una jerarquía

### Compras (Reporting Services)

1. Top de mes en donde más se ha gastado clasificado por año y por semestre. Año->Semestre->Mes. Incluir subtotales.
2. Top de Sucursales que más compraron pudiendo observar la categoría de producto y producto adquirido. Pudiendo ser la sucursal seleccionable o enviada como parámetro.
Sucursal->Categoría Producto ->Producto. Incluir subtotales.
3. Top de mes en donde se hayan comprado el mayor número de unidades clasificadas por año y por semestre. Ordenado por Semestre descendente según unidades. Pudiendo ser el mes seleccionable o enviado como parámetro. Año->Semestre->Mes. Incluir subtotales.

### Ventas (Reporting Services)
1. Top vendedores que han vendido más unidades clasificados por sucursal. Sucursal->Vendedor. Incluir subtotales.
2. Top regiones en donde se ha obtenido el mayor ingreso pudiendo
observar Top de productos clasificados por Grupo de producto en cada región. Pudiendo ser la marca seleccionable o enviada como parámetro. Región->Categoría Producto->Marca Producto->Producto. Incluir subtotales.
3. Top de mes en donde más ingresos se han obtenido clasificado por año y por semestre. Ordenado por semestre ascendentemente según ingresos. Pudiendo ser el semestre seleccionable o enviado como parámetro. Año->Semestre->Mes. Incluir subtotales.


### Real-time Dashboard (Power BI)
1. Realizar un Dashboard (tablero) interactivo en el cual se pueda navegar entre las distintas dimensiones y hechos para elaborar reportes solicitados en tiempo real.


