# Yii2 hotkeysjs

AssetBundle for hotkeys.js

## Installation

#### Composer

```
composer require --prefer-dist "ayrozjlc/yii2-hotkeys:*"
```

or add

```
"ayrozjlc/yii2-hotkeys": "dev-master"
```

to the ```require``` section of your `composer.json` file.

## Usage

in view (for example: ```@app/views/layouts/main.php```)

```php
// ...
use ayrozjlc\hotkeys\HotkeysAsset;
// ...
HotkeysAsset::register($this);
```

or add to your ```assets/AppAsset.php```

```php
public $depends = [
    // ...
    'ayrozjlc\hotkeys\HotkeysAsset',
];
```

Documentation:
[hotkeysjs](https://wangchujiang.com/hotkeys/)
