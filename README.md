Puli Extension for Twig
=======================

[![Build Status](https://travis-ci.org/puli/twig-extension.png?branch=master)](https://travis-ci.org/puli/twig-extension)
[![Build status](https://ci.appveyor.com/api/projects/status/bnnfj371jp7tb9gx/branch/master?svg=true)](https://ci.appveyor.com/project/webmozart/twig-extension/branch/master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/puli/twig-extension/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/puli/twig-extension/?branch=master)
[![Latest Stable Version](https://poser.pugx.org/puli/twig-extension/v/stable.png)](https://packagist.org/packages/puli/twig-extension)
[![Total Downloads](https://poser.pugx.org/puli/twig-extension/downloads.png)](https://packagist.org/packages/puli/twig-extension)
[![Dependency Status](https://www.versioneye.com/php/puli:twig-extension/1.0.0/badge.png)](https://www.versioneye.com/php/puli:twig-extension/1.0.0)

Latest release: [1.0.0-beta6](https://packagist.org/packages/puli/twig-extension#1.0.0-beta6)

PHP >= 5.3.9

With this extension for the [Twig templating engine], you can refer to template
files through [Puli] paths:

```php
echo $twig->render('/acme/blog/views/show.html.twig');
```

Read [Puli at a Glance] if you want to learn more about Puli.

Authors
-------

* [Bernhard Schussek] a.k.a. [@webmozart]
* [The Community Contributors]

Installation/Documentation
--------------------------

Follow the guide [Loading Twig Templates with Puli] to install the extension in
your project. This guide will tell you all you need to know to use the extension.

Contribute
----------

Contributions to are very welcome!

* Report any bugs or issues you find on the [issue tracker].
* You can grab the source code at Puli’s [Git repository].

Support
-------

If you are having problems, send a mail to bschussek@gmail.com or shout out to
[@webmozart] on Twitter.

License
-------

All contents of this package are licensed under the [MIT license].

[Bernhard Schussek]: http://webmozarts.com
[The Community Contributors]: https://github.com/puli/twig-extension/graphs/contributors
[Twig templating engine]: http://twig.sensiolabs.org
[Puli]: http://puli.io
[Loading Twig Templates with Puli]: http://docs.puli.io/en/latest/extensions/twig.html
[Puli at a Glance]: http://docs.puli.io/en/latest/at-a-glance.html
[issue tracker]: https://github.com/puli/issues/issues
[Git repository]: https://github.com/puli/twig-extension
[@webmozart]: https://twitter.com/webmozart
[MIT license]: LICENSE
