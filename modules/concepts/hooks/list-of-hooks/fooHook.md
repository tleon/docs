---
Title: fooHook
hidden: true
hookTitle: ''
files:
    -
        url: 'https://github.com/PrestaShop/PrestaShop/blob/9.0.x/tests/Unit/Core/Hook/HookDispatcherTest.php'
        file: tests/Unit/Core/Hook/HookDispatcherTest.php
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
$this->hookDispatcher->dispatchWithParameters('fooHook', ['bar' => 'Bar']);
```
