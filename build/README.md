# Copyright (C) Tyler R. Drury 13-06-2019, All Rights Reserved

# /php/egpcs

/php/egpcs contains all site-wide in-house php scripts for back-end development for accessing:
    * host
    * client
    * POST
    * GET
    * SERVER
    * SESSION
    * COOKIE and
    * other QUERY related information

## Getting Started

```php
//
//for entire package functionality
//or individual files can be required for specific functionality, to reduce bloat
//
require_once 'php/egpcs/meta.php';
//
use function egpcs/get_echo as _eg;
//
//echos an escaped, json encoded string representing all arguments passed via the URI's query string
eg();
```


## Getting the Library

egpcs.php can be accessed as a hosted service, or request a custom-build for projects here.
For any aspiring developers/contributors, the source code can be accessed on gitHub here.


## License

*egpcs.php* is released under the  the modified Apache 2.0 License, typical of all VS products.
See [LICENSE][7] file for details.

## Links


Authors and contributors are listed in the [AUTHORS.en.txt][8] file.

[1]: http://highlightjs.readthedocs.io/en/latest/api.html#inithighlightingonload
[2]: http://highlightjs.readthedocs.io/en/latest/css-classes-reference.html
[3]: http://highlightjs.readthedocs.io/en/latest/api.html#highlightblock-block
[4]: http://highlightjs.readthedocs.io/en/latest/api.html#configure-options
[5]: https://highlightjs.org/download/
[6]: http://highlightjs.readthedocs.io/en/latest/building-testing.html
[7]: https://github.com/isagalaev/highlight.js/blob/master/LICENSE
[8]: https://github.com/isagalaev/highlight.js/blob/master/AUTHORS.en.txt
