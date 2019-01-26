# Initial commands

```sh
git init
composer init -q
md src/App/Mvc -p
touch index.php src/App/Mvc/{Model,View,Controler}.php
```

## composer.json

```json
{
  "autoload": {
    "psr-4": {
      "App\\": "src/App"
    }
  }
}
```

`composer install`
