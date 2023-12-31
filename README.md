[![Build Status](https://travis-ci.org/OCA/stock-logistics-barcode.svg?branch=10.0)](https://travis-ci.org/OCA/stock-logistics-barcode)
[![Coverage Status](https://img.shields.io/coveralls/OCA/stock-logistics-barcode.svg)](https://coveralls.io/r/OCA/stock-logistics-barcode?branch=10.0)

Odoo Stock Logistic Barcode
===========================


This project aims to deal with modules related to the management of barcode in a generic way. You'll find modules that:

 - Allow to generate bar code each time a object is created
 - Setup bar code on object
 - Print bar code
 - Search and use them with a barcode scanner

Please don't hesitate to suggest one of your module to this project. Also, you may want to have a look on those other projects here:

 - https://github.com/OCA/stock-logistics-tracking
 - https://github.com/OCA/stock-logistics-workflow
 - https://github.com/OCA/stock-logistics-warehouse

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[barcodes_ean14](barcodes_ean14/) | 10.0.1.0.1 |  | It provides an EAN14 barcode nomenclature.
[barcodes_generator_abstract](barcodes_generator_abstract/) | 10.0.1.0.3 |  | Generate Barcodes for Any Models
[barcodes_generator_location](barcodes_generator_location/) | 10.0.1.0.0 |  | Generate Barcodes for Stock Locations
[barcodes_generator_lot](barcodes_generator_lot/) | 10.0.1.0.0 |  | Generate Barcodes for Stock Production Lots
[barcodes_generator_package](barcodes_generator_package/) | 10.0.1.0.0 |  | Generate Barcodes for Product Packaging
[barcodes_generator_partner](barcodes_generator_partner/) | 10.0.1.0.0 |  | Generate Barcodes for Partners
[barcodes_generator_picking](barcodes_generator_picking/) | 10.0.1.0.0 |  | Generate Barcodes for Stock Pickings
[barcodes_generator_product](barcodes_generator_product/) | 10.0.1.0.0 |  | Generate Barcodes for Products (Templates and Variants)
[barcodes_multiline](barcodes_multiline/) | 10.0.1.0.1 |  | It allows barcodes to span multiple lines.
[barcodes_search](barcodes_search/) | 10.0.1.0.2 |  | Search any item by it barcode
[product_packaging_barcode](product_packaging_barcode/) | 10.0.1.0.0 |  | Reimplement barcode field in Product Packagings
[stock_inventory_barcode](stock_inventory_barcode/) | 10.0.0.1.0 |  | Add simple barcode interface on inventories
[stock_scanner](stock_scanner/) | 10.0.1.1.2 |  | Allows managing barcode readers with simple scenarios
[stock_scanner_inventory](stock_scanner_inventory/) | 9.0.1.0.0 |  | Stock Scanner Inventory
[stock_scanner_location_info](stock_scanner_location_info/) | 10.0.1.0.0 |  | Stock Scanner Location Info
[stock_scanner_receipt](stock_scanner_receipt/) | 10.0.1.0.0 |  | Stock Scanner Receipt


Unported addons
---------------
addon | version | maintainers | summary
--- | --- | --- | ---
[barcode_link](barcode_link/) | 1.0 (unported) |  | Barcode link Module
[base_gs1_barcode](base_gs1_barcode/) | 1.0 (unported) |  | Decoding API for GS1-128 (aka UCC/EAN-128) and GS1-Datamatrix
[product_multi_ean](product_multi_ean/) | 1.2 (unported) |  | Multiple EAN13 on products

[//]: # (end addons)
