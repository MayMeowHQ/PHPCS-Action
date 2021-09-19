# PHPCS action by MayMeow

Action to test php with PHPUni. This action using 

* [MayMeow/php-ci-cd](https://github.com/MayMeow/php-ci-cd)

## Usage

add to your workflow

``` yaml
- name: PHPUnit Test by MayMeow
  uses: MayMeowHQ/PHPCS-Action@v5
```

This will run `composer install` and `composer run test`. To run this you will need add to `composer.json` file:

``` json
"codesniffer": "phpcs --standard=PSR12 src",
```
