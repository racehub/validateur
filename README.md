# Validateur, a Clojure(Script) Validation Library

Validateur is a [Clojure(Script) validation library](http://clojurevalidations.info) inspired by Ruby's ActiveModel. Validateur is functional: validators are
functions, validation sets are higher-order functions, validation results are returned as values.


## Supported Clojure versions

Validateur requires Clojure 1.4+/ClojureScript 0.0-2138+.



## Maven Artifacts

Validateur artifacts are [released to Clojars](https://clojars.org/com.novemberain/validateur).
If you are using Maven, add the following repository definition to your `pom.xml`:

``` xml
<repository>
  <id>clojars.org</id>
  <url>http://clojars.org/repo</url>
</repository>
```

### The Latest Release

With Leiningen:

    [com.novemberain/validateur "2.3.1"]

With Maven:

    <dependency>
      <groupId>com.novemberain</groupId>
      <artifactId>validateur</artifactId>
      <version>2.3.1</version>
    </dependency>



## Documentation & Examples

Please refer to the [documentation guides](http://clojurevalidations.info) for Validateur.

Our test suite has usage examples for each validator, built-in validation functions have docstrings.


## Continuous Integration

[![Continuous Integration status](https://secure.travis-ci.org/michaelklishin/validateur.png)](http://travis-ci.org/michaelklishin/validateur)


## Development

Validateur uses [Leiningen 2](https://github.com/technomancy/leiningen/blob/master/doc/TUTORIAL.md). Make
sure you have it installed and then run tests against all supported Clojure versions using

    lein2 do clean, cljx once, all test, cljsbuild test

Then create a branch and make your changes on it. Once you are done with your changes and all
tests pass, submit a pull request on Github.


## License

Copyright (C) 2011-2014 Michael S. Klishin, Alex Petrov, the ClojureWerkz team,
and [contributors](https://github.com/michaelklishin/validateur/graphs/contributors).

Distributed under the Eclipse Public License, the same as Clojure.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/michaelklishin/validateur/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
