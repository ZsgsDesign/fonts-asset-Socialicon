# fonts-asset-Socialicon
Socialicon for composer.

## Install

```bash
composer require oomphinc/composer-installers-extender
composer require fonts-asset/socialicon
```

And in `composer.json`:

```json
    "extra": {
        "installer-types": [
            "fonts-asset"
        ],
        "installer-paths": {
            "public/fonts/{$name}": [
                "type:fonts-asset"
            ]
        }
    },
```

## Usage

```html
<link rel="stylesheet" href="/fonts/socialicon/socialicon.css">
```

## Credit

[ZsgsDesign](https://github.com/ZsgsDesign)