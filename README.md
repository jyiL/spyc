Spyc
===============
[![Latest Stable Version](https://poser.pugx.org/ljy/spyc/v/stable)](https://packagist.org/packages/ljy/spyc)
[![Total Downloads](https://poser.pugx.org/ljy/spyc/downloads)](https://packagist.org/packages/ljy/spyc)
[![Latest Unstable Version](https://poser.pugx.org/ljy/spyc/v/unstable)](https://packagist.org/packages/ljy/spyc)
[![License](https://poser.pugx.org/ljy/spyc/license)](https://packagist.org/packages/ljy/spyc)



**Spyc** is a YAML loader/dumper written in pure PHP. Given a YAML document, Spyc will return an array that
you can use however you see fit. Given an array, Spyc will return a string which contains a YAML document 
built from your data.

**YAML** is an amazingly human friendly and strikingly versatile data serialization language which can be used 
for log files, config files, custom protocols, the works. For more information, see http://www.yaml.org.

Spyc supports YAML 1.0 specification.

## Using Spyc

Using Spyc is trivial:

```php
<?php
use Spyc\Spyc;
$Data = Spyc::YAMLLoad('spyc.yaml');
```

or (if you prefer functional syntax)

```php
<?php
use Spyc\Spyc;
$Data = spyc_load_file('spyc.yaml');
```

## License

Spyc is open-sourced software licensed under the [WTFPL license](http://www.wtfpl.net/about/).
