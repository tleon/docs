---
Title: actionCronJob
hidden: true
hookTitle: ''
files:
    -
        url: 'https://github.com/PrestaShop/PrestaShop/blob/9.0.x/tests/Resources/modules/cronjobs/controllers/admin/AdminCronJobsController.php'
        file: tests/Resources/modules/cronjobs/controllers/admin/AdminCronJobsController.php
locations:
    - 'back office'
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
Hook::exec('actionCronJob', [], $cron['id_module']);
```
