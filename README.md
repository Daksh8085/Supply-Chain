# Supply Chain Analytics

## Functions

1. Import and integrate supply chain data
2. Preprocess inventory and shipping data
3. Create interactive supply chain visualizations
4. Deploy inventory optimization models

## Tasks

- What factors cause supply chain bottlenecks?
- How do seasonal patterns affect inventory needs?
- Which visualizations techniques best show supply flow?
- What features best predict delivery delays?
- How effective are different optimization strategies?
- What is the impact of external events on supply chain?
- How can we optimize inventory levels?

## Data Set

### Order Details

- `Type`: Payment method used for the order (eg. DEBIT, CASH, PAYMENT, TRANSFER)
- `Order Id`: Unique identifier for the order (eg. 77202)
- `Order Status`: The current status of the order (eg. COMPLETE, PENDING, CLOSED)
- `Order date (DateOrders)`: The date and time the order was placed (eg. 1/31/2018 22:56)
- `Shipping date (DateOrders)`: The scheduled shipping date and time (eg. 2/3/2018 22:56)
- `Shipping Mode`: The mode of shipping (eg. Standard Class)

### Shipping and Delivery

- `Days for shipping (real)`: Actual days taken to ship the order (eg. 3 days)
- `Days for shipment (scheduled)`: Scheduled days expected for shipping (eg. 4 days)
- `Delivery Status`: Whether the shipping is on the time or delayed (eg. Advance shipping)
- `Late_delivery_risk`: Binary indicator of late delivery risk (eg. 0 for no risk, 1 for risk)

### Financials

- `Benefit per order`: Profile earned from the order (eg. 91.25)
- `Sales per customer`: Total sales amount for the customer (eg. 314.64)
- `Order Item Product Price`: Price per Product in the order (eg. 327.75)
- `Order Item Discount`: Discount applied to the order item (eg. 13.11)
- `Order Item Discount Rate`: Discount rate in percentage (eg. 0.04 or 4%)
- `Order Item Profit Ratio`: Profit as a percentage of the product price (eg. 0.29 or 29%)

### Customer Information

- `Customer Fname/Lname`: First and last name of the customer (eg. cally Holloway)
- `Customer Id`: Unique identifier for the customer (eg. 20755)
- `Customer Email/Password`: Placeholder data (drop it)
- `Customer City/State/Country`: Geographical information about the customer (eg. Caguas, PR, Puerto Rico)
- `Customer Street/Zipcode`: Address details (eg. 5365 Noble Nectar Island, 725.0)

### Product Information

- `Product Name`: Name of the product (eg. Smart watch)
- `Product Price`: Listed price of the product (eg. 327.75)
- `Product Status`: Status code for the product (eg. 0 for active)
- `Product Category Id`: Unique identifier for the product category (eg. 73)
- `Product Description/Product Image`: Description and image URL of the product (drop it)

### Geographical and Market Data

- `Latitude/Longitude`: Coordinates related to the order or customer location (eg. 18.251453, -66.037056)
- `Market`: The market where the transaction occurred (eg. Pacific Asia)
- `Order City/Country`: Geographical location of the order (eg. Bekasi, Indonesia)
- `Order Region/State`: Regional details of the order (eg. Southeast Asia, Java Occidental)

### Department and Category

- `Department Id/Name`: Department associated with the product (eg. 2, Fitness)
- `Category Id/Name`: Category of the product (eg. 73, Sporting Goods)
