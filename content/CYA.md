
**VENTAS**

model: sale.order

name: Cotización / Pedido de Ventas

*Campos Nativos*

partner_id: Cliente

partner_invoice_id: Dirección de factura

partner_shipping_id: Dirección de entrega

commitment_date: Fecha de entrega

date_order: Fecha de la orden

user_id: Vendedor

team_id: Equipo de ventas

activity_ids: Actividades

invoice_ids: Facturas

picking_ids: Traslados

purchase_order_count: Número de órdenes de compra generadas

client_order_ref: Referencia del cliente

warehouse_id: Almacén

validity_date: Vencimiento

pricelist_id: Lista de precios

payment_term_id: Términos de pago (Se usa para dete)

sale_order_template_id: [[#^21b1d1| Example]]



*Campos Desarrollados*
analytic_distribution:
type_id:
custom_date:

*Vista*
![[Pasted image 20240712163213.png]]

model: sale_order_lines
name: Líneas de la orden
product_id:
order_line_image:








---


# Plantillas de cotización

^21b1d1


Los vendedores pueden crear plantillas que pueden volver a usar para productos en común o servicios que ofrece el negocio.
Al usar estas plantillas, las cotizaciones se pueden hacer y enviar mucho más rápido a los clientes sin tener que crear cotizaciones nuevas desde cero cada vez que se realiza una negociación de ventas.
