#Generowanie entities z bazy

$ php bin/console doctrine:mapping:import --force MainBundle xml+
$ php bin/console doctrine:mapping:convert annotation ./src+
$ php bin/console doctrine:generate:entities MainBundle
