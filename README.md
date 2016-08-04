# Magento Developer Meta

Install valuable Magento 1.x development tools with this meta package.

## Meta Package?

> An empty package that contains requirements and will trigger their installation, but contains no files and will not write anything to the filesystem. As such, it does not require a dist or source key to be installable.

[Composer Schema Types](https://getcomposer.org/doc/04-schema.md#type)

## Tools

### AOEpeople - Advanced Template Hints

> `Aoe_TemplateHints` extends the default Magento "Template Hints" developer functionality by adding more information for each block.

[https://github.com/AOEpeople/Aoe_TemplateHints](https://github.com/AOEpeople/Aoe_TemplateHints)

[http://fbrnc.net/blog/2012/10/magento-advanced-template-hints-20](http://fbrnc.net/blog/2012/10/magento-advanced-template-hints-20)

### AOEpeople - Profiler

>  `Aoe_Profiler` is a drop-in replacement for the `Varien_Profiler`. It can be activated in the configuration and doesn’t require you to change any core files. It captures all data and also records its hierarchal information and displays everything in a nice way..

[http://fbrnc.net/blog/2012/08/magento-profiler](http://fbrnc.net/blog/2012/08/magento-profiler)

[https://github.com/AOEpeople/Aoe_Profiler](https://github.com/AOEpeople/Aoe_Profiler)


### Mario Oprea - Magento Debug

> This repository represents an extension for Magento 1.x that offers a developer debug toolbar. The idea came from robhudson's django-debug-toolbar. Latest version is based on Symfony's WebProfilerBundle UI.

[https://github.com/madalinoprea/magneto-debug](https://github.com/madalinoprea/magneto-debug)

## Install

With the Magento Composer Installer Via Packagist

```
composer.phar require bennoislost/magento-developer-meta
```

Some packages may require you to add the "Firegento" repository to your projects `composer.json`

```
{
    "repositories": [
        {
            "type": "composer",
            "url": "https://packages.firegento.com"
        }
    ]
}
```

See [https://github.com/Cotya/magento-composer-installer](https://github.com/Cotya/magento-composer-installer) for common installation problems.

Some packages may require running of setup or config resources for a full installation....

* `madalinoprea/magneto-debug` - Setup resource for additional query logging
* `oepeople/aoe_templatehints` - Remove `dev/restrict/allow_ips` config path or set correctly & depending on your projects Magento Composer Module install type set `dev/template/allow_symlink` to 1.

If you are not familiar with these tools please see the related package repository for installation instructions and FAQ's.

## Contribution

If you would like to add / remove a package, please submit a Pull Request.

