# Simple Warehouse Project

### About
This project has a Spring Boot Rest API called warehousebackend and a REACTJS application called warehouse_frontend.
The project is to enable clients find warehouses with products they need and to also enable warehouse owners create offers
that are good for their customers.

### Guides

* [Click here to view the application.](https://warehousems.netlify.app)

### Applications
<b> warehousebackend</b>

Warehouse-backend application exposes a REST API to manage warehouses.
Its secured endpoints can be just accessed if an access token (JWT) is provided

warehousebackend stores its data in a Postgresql database.

<b>warehouse_frontend</b>

warehouse_frontend is where users can find and save warehouses and warehouse owners can create offers. In order to access the application, a user/warehouse-owner must login using their username and password. All requests coming from the warehouse_frontend to the secured endpoints in the warehousebackend have an access token (JWT) that is generated when a login happens.

warehouse_front uses semantic UI React as CSS-styled framework.




