

---

# Target Sales Dataset (Brazil: 2016-2018)

## Overview

This dataset provides comprehensive information on Target's e-commerce operations in Brazil, covering 100,000 orders placed between 2016 and 2018. Target, a globally recognized brand and a leading retailer in the United States, is known for its exceptional value, inspiration, innovation, and unique shopping experience. This dataset is valuable for analyzing various aspects of Target's operations, from order processing and pricing strategies to payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction.

## Dataset Features

The dataset is divided into 8 CSV files:

1. **customers.csv**
2. **sellers.csv**
3. **order_items.csv**
4. **geolocation.csv**
5. **payments.csv**
6. **orders.csv**
7. **products.csv**

### Detailed Description of Files and Features

#### 1. customers.csv
- **customer_id**: Unique identifier for the customer
- **customer_unique_id**: Unique identifier for the customer (unique across the dataset)
- **customer_zip_code_prefix**: Zip code prefix of the customer's location
- **customer_city**: City of the customer's location
- **customer_state**: State of the customer's location

#### 2. sellers.csv
- **seller_id**: Unique identifier for the seller
- **seller_zip_code_prefix**: Zip code prefix of the seller's location
- **seller_city**: City of the seller's location
- **seller_state**: State of the seller's location

#### 3. order_items.csv
- **order_id**: Unique identifier for the order
- **order_item_id**: Identifier for items in the order
- **product_id**: Unique identifier for the product
- **seller_id**: Unique identifier for the seller
- **shipping_limit_date**: Deadline for shipping the order
- **price**: Price of the product
- **freight_value**: Freight value of the order

#### 4. geolocation.csv
- **geolocation_zip_code_prefix**: Zip code prefix for geolocation
- **geolocation_lat**: Latitude of the location
- **geolocation_lng**: Longitude of the location
- **geolocation_city**: City of the geolocation
- **geolocation_state**: State of the geolocation

#### 5. payments.csv
- **order_id**: Unique identifier for the order
- **payment_sequential**: Payment sequential number
- **payment_type**: Type of payment
- **payment_installments**: Number of payment installments
- **payment_value**: Value of the payment

#### 6. orders.csv
- **order_id**: Unique identifier for the order
- **customer_id**: Unique identifier for the customer
- **order_status**: Status of the order
- **order_purchase_timestamp**: Timestamp of the order purchase
- **order_approved_at**: Timestamp of the order approval
- **order_delivered_carrier_date**: Date when the order was delivered to the carrier
- **order_delivered_customer_date**: Date when the order was delivered to the customer
- **order_estimated_delivery_date**: Estimated date of order delivery

#### 7. products.csv
- **product_id**: Unique identifier for the product
- **product_category_name**: Name of the product category
- **product_name_length**: Length of the product name
- **product_description_length**: Length of the product description
- **product_photos_qty**: Number of photos of the product
- **product_weight_g**: Weight of the product in grams
- **product_length_cm**: Length of the product in centimeters
- **product_height_cm**: Height of the product in centimeters
- **product_width_cm**: Width of the product in centimeters

### Potential Use Cases

Analyzing this dataset can offer valuable insights into:
- Order processing and fulfillment
- Pricing strategies and trends
- Payment and shipping performance
- Customer demographics and purchasing behavior
- Product attributes and their impact on sales
- Customer satisfaction and review analysis

## Usage

The dataset can be used for various analytical purposes including:
- Data analysis and visualization
- Machine learning model training
- Market research and business strategy development
- Academic research and case studies




