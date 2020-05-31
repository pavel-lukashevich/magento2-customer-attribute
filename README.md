Magento Community Edition 2.3.4.
- Разработать модуль , который добавляет новый атрибут для пользователей ( тип атрибута - text field ).
- Реализовать отображение и сохранение этого атрибута на странице редактирования пользователя в админке. Отображать в аккаунте пользователя на фронтенде не нужно. 

установка:
- скачать архив https://github.com/pavel-lukashevich/magento2-customer-attribute/archive/master.zip
- распаковать архив
- из папки `magento2-customer-attribute-master` скопировать папку `Lukashevich` в свой проект в папку `app/code`
- включить модуль `php bin/magento module:enable Lukashevich_CustomerAttribute`
- выполнить команды 
```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```
