# Test project for a possible PHPUnit bug

```bash
composer install
./vendor/bin/phpunit --migrate-configuration -c FailOnDeprecation.xml
./vendor/bin/phpunit --migrate-configuration -c FailOnNotice.xml
```