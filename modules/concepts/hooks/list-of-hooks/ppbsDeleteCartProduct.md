---
Title: ppbsDeleteCartProduct
hidden: true
hookTitle: ''
files:
    -
        url: 'https://github.com/PrestaShop/PrestaShop/blob/9.0.x/tests/Resources/modules_tests/override_for_unit_test/classes/Cart.php'
        file: tests/Resources/modules_tests/override_for_unit_test/classes/Cart.php
locations:
    - 'front office'
type: action
hookAliases: 
array_return: false
check_exceptions: false
chain: false
origin: core
description: ''

---

{{% hookDescriptor %}}

## Call of the Hook in the origin file

```php
Hook::exec(
            'ppbsDeleteCartProduct',
            [
                'id_product' => $id_product,
                'id_product_attribute' => $id_product_attribute,
                'id_customization' => $id_customization,
                'id_address_delivery' => $id_address_delivery,
            ],
            null,
            false
        );
```
