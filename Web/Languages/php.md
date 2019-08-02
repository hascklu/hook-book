# PHP

- Convert an hex string to ASCII:
```php
urldecode();
```

- Output a php script on a server without execute it:
```
openssl base64 -in index.php
```
We can also use a ```tail``` so we can print it from the end and skip ```<?php``` who execute it.