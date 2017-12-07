[![Latest Stable Version](https://poser.pugx.org/jonnitto/image/v/stable)](https://packagist.org/packages/jonnitto/image)
[![Total Downloads](https://poser.pugx.org/jonnitto/image/downloads)](https://packagist.org/packages/jonnitto/image)
[![License](https://poser.pugx.org/jonnitto/image/license)](LICENSE)
[![GitHub forks](https://img.shields.io/github/forks/jonnitto/Jonnitto.Image.svg?style=social&label=Fork)](https://github.com/jonnitto/Jonnitto.Image/fork)
[![GitHub stars](https://img.shields.io/github/stars/jonnitto/Jonnitto.Image.svg?style=social&label=Stars)](https://github.com/jonnitto/Jonnitto.Image/stargazers)
[![GitHub watchers](https://img.shields.io/github/watchers/jonnitto/Jonnitto.Image.svg?style=social&label=Watch)](https://github.com/jonnitto/Jonnitto.Image/subscription)
[![GitHub followers](https://img.shields.io/github/followers/jonnitto.svg?style=social&label=Follow)](https://github.com/jonnitto/followers)
[![Follow Jon on Twitter](https://img.shields.io/twitter/follow/jonnitto.svg?style=social&label=Follow)](https://twitter.com/jonnitto)

Jonnitto.Image Package for Neos CMS
===================================

With this package you add a image NodeType into [Neos CMS](https://www.neos.io).  
Contributions are very welcome!


If you want to get a fast overview, take a look at [Settings.yaml](Configuration/Settings.yaml) and [NodeTypes.yaml](Configuration/NodeTypes.yaml) in the [Configuration](Configuration) folder.


Installation
------------
Most of the time you have to make small adjustments to a package (e.g. configuration in Settings.yaml). Because of that, it is important to add the corresponding package to the composer from your theme package. Mostly this is the site packages located under Packages/Sites/. To install it correctly go to your theme package (e.g.Packages/Sites/Foo.Bar) and run following command:

```bash
composer require jonnitto/image --no-update
```

The --no-update command prevent the automatic update of the dependencies. After the package was added to your theme composer.json, go back to the root of the Neos installation and run composer update. Et voilà! Your desired package is now installed correctly.



License
-------

Licensed under MIT, see [LICENSE](LICENSE)
