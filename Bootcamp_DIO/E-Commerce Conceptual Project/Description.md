This is a conceptual project for an e-commerce database, centered on a multiseller plataform, done in MySQL Workbench.

The e-commerce plataform contains:
- Clients;
- Products;
- Stocks;
- Suppliers;
- Orders.

The requirements were:

PRODUCTS
- The products are selled on an unique online plataform, and can have distinc sellers (outsourced);
- Each product has only one supplier;
- The order can contain one or many products.

CLIENT
- The client can be PF or PJ, but can choose only one to order;
- The client can register with CPF or CNPJ;
- The client's address will determine the shipping price;
- A client can make multiple orders;
- There's a period for product devolution;
- The client can register many payment methods.

ORDER
- The order is made by the client, and hold informations about the sale, address and shipping status;
- One or more products can make an order;
- The order can be cancelled;
- The shipping has a tracking code.

SUPPLIER AND STOCK
- A supplier have only one stock;
- A stock can be used by one or more suppliers.