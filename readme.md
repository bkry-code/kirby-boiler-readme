# Kirby Boiler Readme

![Version](https://img.shields.io/badge/version-1.0.0-green.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg) ![Kirby Version](https://img.shields.io/badge/Kirby-2.0%2B-red.svg)

*Version 1.0.0*

Write a short description of what the plugin is about. If you can, add an animated gif or screenshot. It will probably make more people use your plugin.

![](https://placeholdit.imgix.net/~text?txtsize=38&txt=Screenshot&w=888&h=150&txttrack=0)

## Installation

### [Kirby CLI](https://github.com/getkirby/cli)

Run this command:

```
kirby plugin:install github-name/kirby-your-plugin
```

### Manually

Add the folder `kirby-your-plugin` into `/site/plugins/`.

## Setup

### 1. Blueprint

If your plugin requires a blueprint setup, this may be a good start:

```
fields:
  yourfield:
    title: Your Field
    type: yourfield
```

### 2. Add JS to your footer

If your plugin uses assets, this may be a good start:

```php
echo js('assets/plugins/kirby-your-plugin/js/script.js');
```

## Usage

Describe how to use this plugin. Text, images, videos etc is good here.

## Options

### A plugin option

Describe the option and always set the second argument as the default.

```
c::set('plugin.your.plugin.option', 'Default value');
```

## Changelog

**1.0.0**

- Add the items in a descending order 

**0.5.1**

- Some important change
- Initial release

## Todo

- [ ] An uncompleted task
- [x] ~~A completed task~~

## Requirements

- Kirby 2.0+

## License

MIT

## Credits

- [Jens Törnell](https://github.com/jenstornell)
- [Mathieu Etienne](https://github.com/Thiousi/)