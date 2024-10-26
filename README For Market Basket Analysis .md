## Market Basket Analysis

This project aims to perform market basket analysis using data from the Olist platform. It employs techniques such as frequent pattern mining and association rules to explore consumer behavior patterns.

### Dataset Information

This project utilizes four main datasets:

1. **order_items_df**: Contains details of the items ordered in each order.
   - **Source**: `olist_order_items_dataset.csv`
   - **Columns**: 
     - `order_id`: Unique identifier for the order
     - `order_item_id`: Unique identifier for the order item
     - `product_id`: Unique identifier for the product
     - `seller_id`: Unique identifier for the seller
     - `shipping_limit_date`: Shipping limit date
     - `price`: Price of the product
     - `freight_value`: Value of the freight

2. **orders_df**: Contains general information about the orders.
   - **Source**: `olist_orders_dataset.csv`
   - **Columns**:
     - `order_id`: Unique identifier for the order
     - `customer_id`: Unique identifier for the customer
     - `order_status`: Status of the order
     - `order_purchase_timestamp`: Date and time of order purchase
     - `order_approved_at`: Date and time of order approval
     - `order_delivered_carrier_date`: Date the order was delivered to the carrier
     - `order_delivered_customer_date`: Date the order was delivered to the customer
     - `order_estimated_delivery_date`: Estimated delivery date

3. **products_df**: Contains information about the products.
   - **Source**: `olist_products_dataset.csv`
   - **Columns**:
     - `product_id`: Unique identifier for the product
     - `product_category_name`: Name of the product category
     - `product_name_length`: Length of the product name
     - `product_description_length`: Length of the product description
     - `product_photos_qty`: Number of product photos
     - `product_weight_g`: Weight of the product in grams
     - `product_length_cm`: Length of the product in centimeters
     - `product_height_cm`: Height of the product in centimeters
     - `product_width_cm`: Width of the product in centimeters
     - `price`: Price of the product

4. **category_translation_df**: Contains translations of product categories.
   - **Source**: `product_category_name_translation.csv`
   - **Columns**:
     - `product_category_name`: Name of the product category
     - `product_category_name_english`: Name of the product category in English

### Requirements

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - mlxtend

### How to Run

1. Ensure all required libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn mlxtend
   ```

2. Download the data files into the same directory as the Jupyter Notebook.

3. Open the `MarketBasket_Analysis.ipynb` file in Jupyter or Google Colab.

4. Run the cells to analyze the data.


### License

This project is licensed under the [MIT License](LICENSE).
