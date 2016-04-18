[![NPM version](https://img.shields.io/npm/v/hjson.svg?style=flat-square)](http://www.npmjs.com/package/hjson)
[![Maven Central](https://img.shields.io/maven-central/v/org.hjson/hjson.svg?style=flat-square)](http://search.maven.org/#search&#124;ga&#124;1&#124;g%3A%22org.hjson%22%20a%3A%22hjson%22)
[![PyPI version](https://img.shields.io/pypi/v/hjson.svg?style=flat-square)](https://pypi.python.org/pypi/hjson)
[![nuget version](https://img.shields.io/nuget/v/Hjson.svg?style=flat-square)](https://www.nuget.org/packages/Hjson/)
[![Packagist](https://img.shields.io/packagist/v/laktak/hjson.svg?style=flat-square)](https://packagist.org/packages/laktak/hjson)

# Hjson, the Human JSON

A configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.

## Intro

```
{
  # specify rate in requests/second (because comments are helpful!)
  rate: 1000

  // prefer c-style comments?
  /* feeling old fashioned? */

  # did you notice that rate doesn't need quotes?
  hey: look ma, no quotes for strings either!

  # best of all
  notice: []
  anything: ?

  # yes, commas are optional!

  # Obviously you can always use standard JSON syntax as well:
  favNumbers: [ 1, 2, 3, 6, 42 ]
}
```

For details see [hjson.org](http://hjson.org).
