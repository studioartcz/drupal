# Varnish Cache

If you want to use [Varnish Cache](https://varnish-cache.org/) for your project, we are recommend these steps:

1. add varnish modules:
    ```
    composer require drupal/purge
    composer require drupal/purge_purger_http
    ```
    
2. allow them:
    ```
    cd docroot
    ../bin/drush en purge -y
    ../bin/drush en purge_purger_http -y
    ```
    
3. setup modules
    
    **@todo:** add screenshots about config