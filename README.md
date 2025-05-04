# mapping-domains-DDD

## entities identified:
* Product
> id, name, price, color, size, fornecedor, minStock
* Sale
> id, date, productId, quantity
* Stock
> id, productId, quantity
* Supliers
> id, name, contactInfo

## use-cases identified:
* Create/update a product
* Create/update a supplier
* Create/update a stock
* Low stock alert
* Stock trends by season
* Automatic purchase orders based on stock levels and trends
* Integration with supplier delivery deadlines
* Summary of sales
