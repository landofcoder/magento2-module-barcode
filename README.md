# Magento 2 Module Lof Barcode Suite

The module will auto setup there sub modules:
- [BarcodeInventory](https://github.com/landofcoder/module-pos-barcode-inventory)
- [BarcodeLabel](https://github.com/landofcoder/module-pos-barcode-label)
- [MultiBarcode](https://github.com/landofcoder/module-pos-multi-barcode)

## Main Features
- Generate barcode by inventory, mutil source stock
- Add product to cart with barcode (GraphQl, REST API)
- query find products by barcode (GraphQl, REST API)
- Barcode Label for Magento 2: Using this POS add-on, the store owner can design customized barcode labels/stickers for products.
- Display price, product name, logo, date, product custom attribute on the barcode labels. The admin can multi-select barcode labels and preview them before printing.
- Support generate barcode for multi source products
- Compatible with MSI of magento 2.3.6-2.4.x

## How to setup?

Setup via composer with command:
```
composer require landofcoder/module-barcode-suite
```

Then run magento 2 commands:
```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
php bin/magento indexer:reindex
```

## User Guide
- [User Guide](https://landofcoder.gitbook.io/magento-2-barcode-suite/)