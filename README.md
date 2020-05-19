Project training for symfony 4
This appli 


This application presents a list of animals, with a data table relation game. For example, a dog belongs to the mamifer family, it is present on several continents, and has one or more owners.

We can filter the list of animals according to a continent, a family or an owner.


Using the project : 

Clone the repo on your environment,
Then install composer "composer install"

To install the database:
php bin/console doctrine:database:create

To start a migration : 
php bin/console doctrine:migrations:migrate

To start a fixture :
php bin/console doctrine:fixtures:load


-To start the server: symfony server:start
