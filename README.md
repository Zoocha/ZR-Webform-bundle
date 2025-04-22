# ZR Webform Bundle Installation Guide

To install the ZR Webform Bundle, follow the steps below:

1. Ensure the below has been added to the `composer.json` **installer-paths**
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
2. Run `composer require zr/zr-webform-bundle`
3. Run the following command (within `/web` directory):

    ```sh
    ddev drush recipe recipes/custom/zr-webform-bundle
    ```
