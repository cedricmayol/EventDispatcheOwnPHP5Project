# EventDispatcheOwnPHP5Project
This is an example for EventDispatcher With Symfony bundle

# INSTALL COMPOSER DEPENDENCY 
composer install
# CREATE A TMP FILE FOR LOGGER 
touch /tmp/log.log 
# EXECUTE CLASS WITH PHP-CLI 
php php src/Vendor/MyAppEventDispatcher/Person.php or on apache with 
php -S localhost:8080
SEE LOGGER tail -f /tmp/log.log
