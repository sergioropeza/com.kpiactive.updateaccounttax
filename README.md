
# Actualización de asiento contables de IVA

Este plugin actualiza el monto IVA pagado y no pagado de los asientos contables de la factura de ventas y compras.

Dicha actualización se realiza al momento de completar o anular una asignación de Pago/cobro. 


## Configuración 

En la pestaña _Contabilidad_ de la ventana de _Tasa de Impuesto_ se encuentra 2 campos:
- Impuesto Pagado al Vender
- Impuesto Pagado al Comprar
  
El cual contedrá las cuentas contables para los asientos contables del Iva Pagado. 

## Menú Actualización de Cuentas Contables de Impuestos
En el menú se encuentra un proceso llamado Actualizar Cuentas Contables de Impuestos el cual recalculará las cuentas de facturas. El objetivo de este proceso es actualizar o recalcular los asientos contables de iva de las Factura(s) de forma manual, ya que al re-contabilizar se pierde el calculo para los campos mencionados anteriormente

 #### Caso de Uso

1- Factura:
- monto base = 90
- IVA = 10
- Total = 100

2 Pago (Equivalente al 50% de la factura):
- monto: 50 

Al asignar el Pago a la factura el asiento contable  para el IVA quedaría de la siguiente manera (Cuentas contables solo de referencia):

- Iva no pagado: 5
- Iva Pagado: 5


