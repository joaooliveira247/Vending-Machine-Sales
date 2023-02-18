# 🏪 Vending Machine Sales

This project uses a dataset's from [kaggle](https://www.kaggle.com/).

<details>
  <summary style="font-size: 20px;"> Vending Machine Sales DataSet Informations</summary>

<br>

- [Vending Machine Sales](https://www.kaggle.com/datasets/awesomeasingh/vending-machine-sales)


|Status|Represents if the machine data is successfully processed|
|:---:|:---:|
|Device ID|Unique electronic identifier ( also called as ePort) for the vending machine. A machine is allocated a unique ePrt * device|
|Location|Indicates location of the vending machine|
|Machine|User-friendly machine name|
|Product|Product vended from the machine|
|Category| Carbonated / Food / Non-carbonated / Water|
|Transaction| Unique identifier for every transaction|
|TransDate | The Date & time of transaction|
|Type | Type of transaction ( Cash / Credit )|
|RCoil | Coil # used to vend the product|
|RPrice | Price of the Product|
|RQty | Quantity sold. This is usually one but machines can be configured to sell more items in a single transaction|
|MCoil | Mapped coil # used to vend the product ( from toucan )|
|MPrice | Mapped price of the Product|
|MQty | Mapped quantity sold. This is usually one but machines can be configured to sell more items in a single transaction|
|LineTotal | Total sale per transaction|
|TransTotal | Represents total of all transactions that will show up on the Credit Card. A user could vend a drink for $3 and a snack for $1.5 making a total of $4.50|
|Prcd Date | Date when the transaction was processed by SeedLive ( an entity that is used to aggregate all transactions electronically )|

</details>

<details>
  <summary style="font-size: 20px;">WallMart Product DataSet Informations</summary>

<br>

[WallMart Product](https://www.kaggle.com/code/waleedgul/price-of-product-wallmart/data)


|Column name|Description|Type|
|:---:|:---:|:---:|
|SHIPPING_LOCATION| The location where the product is shipped from. |String|
|DEPARTMENT| The department in which the product is categorized. |String|
|CATEGORY| The category in which the product is categorized. |String|
|SUBCATEGORY| The subcategory in which the product is categorized. |String|
|BREADCRUMBS| The breadcrumbs for the product. |String|
|SKU| The SKU for the product. |String|
|PRODUCT_URL| The URL for the product. |String|
|PRODUCT_NAME| The name of the product.|String|
|BRAND| The brand of the product. |String|
|PRICE_RETAIL| The retail price of the product. |Float|
|PRICE_CURRENT| The current price of the product. |Float|
|PRODUCT_SIZE| The size of the product. |String|
|PROMOTION| The promotion for the product. |String|
|RunDate| The date on which the data was collected. |Date|
</details>