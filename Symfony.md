#Generowanie entities z bazy
```php
//Import z bazy
$ php bin/console doctrine:mapping:import --force MainBundle xml
//Wygenerowanie entities i dodanie annotations
$ php bin/console doctrine:mapping:convert annotation ./src
//Generowanie setterów i getterów
$ php bin/console doctrine:generate:entities MainBundle
```
