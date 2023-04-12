# laminas-mvc-console

> This package is **abandoned** and will receive no further development!
>
> We recommend using [laminas/laminas-cli](https://docs.laminas.dev/laminas-cli/).

[![Build Status](https://travis-ci.com/laminas/laminas-mvc-console.svg?branch=master)](https://travis-ci.com/laminas/laminas-mvc-console)
[![Coverage Status](https://coveralls.io/repos/github/laminas/laminas-mvc-console/badge.svg?branch=master)](https://coveralls.io/github/laminas/laminas-mvc-console?branch=master)

#
### 2023-04-12 - Update Notes - greg-fischer
#
I've included minor changes for PHP 8 composer config as other forks have done.  This fork also uses greg-fischer/laminas-console updates.

I also included some updates to RouteNotFoundStrategy.php in another fork by: Tigran Makaryan
https://github.com/developer-devPHP/laminas-mvc-console/commit/e35a734c79fabfc6d033e88ae727d33aed013d2b

This appears to help for PHP 8.1, but I have not tested.

Our console MVC code seems to work ok in PHP 8.2 so far, but our code is quite simple and may not use enough of the features to cause errors.



#
### Description
#
laminas-mvc-console provides integration between:

- laminas-console
- laminas-mvc
- laminas-router
- laminas-view

and replaces the console functionality found in the v2 releases of the latter
three components.

- File issues at https://github.com/laminas/laminas-mvc-console/issues
- Documentation is at https://docs.laminas.dev/laminas-mvc-console/

## Installation

```console
$ composer require laminas/laminas-mvc-console
```

Assuming you are using the [component
installer](https://docs.laminas.dev/laminas-component-installer), doing so
will enable the component in your application, allowing you to immediately start
developing console applications via your MVC. If you are not, please read the
[introduction](https://docs.laminas.dev/laminas-mvc-console/intro/) for
details on how to register the functionality with your application.

## For use with laminas-mvc v3 and up

While this component has an initial stable release, please do not use it with
laminas-mvc releases prior to v3, as it is not compatible.

## Migrating from laminas-mvc v2 console to laminas-mvc-console

Please see the [migration guide](http://docs.laminas.dev/laminas-mvc-console/migration/v2-to-v3/)
for details on how to migrate your existing laminas-mvc console functionality to
the features exposed by this component.
