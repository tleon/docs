---
Title: displayBackOfficeFooter
hidden: true
hookTitle: 'Administration panel footer'
files:
    -
        url: 'https://github.com/PrestaShop/PrestaShop/blob/9.0.x/admin-dev/themes/default/template/footer.tpl'
        file: admin-dev/themes/default/template/footer.tpl
locations:
    - 'back office'
type: display
hookAliases: displayBackOfficeFooter
array_return: false
check_exceptions: false
chain: false
origin: core
description: 'This hook is displayed within the admin panel''s footer'

---

{{% hookDescriptor %}}

## Call of the Hook in the origin file

```php
{hook h="displayBackOfficeFooter"};
```
