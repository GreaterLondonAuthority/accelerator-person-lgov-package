# Accelerator person package

This project contains site specific component for the Person package used by the london.gov.uk instance of the GLA drupal accelerator

# installation
This project is downloaded using composer
```
composer require gla/accelerator_person_lgov_package
```

```
   {
       "require": {
           "gla/accelerator_person_lgov_package": "^1.0"
       }
   } 
```




Note: This project is currently accessible through a private pakagist, 
```
    "repositories": [
        {
            "type": "composer",
            "url": "https://repo.packagist.com/greaterlondonauthori/"
        }
   ]
```

and will need an auth key/token
```
   {
      "http-basic": {
          "repo.packagist.com": {
              "username": "<USERNAME>",
              "password": "<TOKEN>"
          }
      }
   }
```
