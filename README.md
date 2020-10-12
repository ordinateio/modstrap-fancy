# modstrap-fancy

Adaptation for jQuery.FancyBox.

## Installation

To install a specific version:
```shell script
npm i https://github.com/callisto2410/modstrap-fancy.git#v1.0.0
```

To install the current version:
```shell script
npm i https://github.com/callisto2410/modstrap-fancy.git
```

## Usage

```javascript
import Fancy from "@modstrap/fancy";
Fancy.init();

$('.button').on('click', () => {
    Fancy.open({
        src: $('.content'),
        type: 'html',
        opts: {
            caption: 'Content description...'
        }
    });
});
```
