# Hypixel PHP

This is a PHP wrapper for the [Hypixel Public API](https://api.hypixel.net)
You can find Documentation and a Java implementation here: https://github.com/HypixelDev/PublicAPI

## Requirements
- PHP 7+
- Hypixel API key

## Installation

The preferred method of installing this library is with
[Composer](https://getcomposer.org/) by running the following from your project
root:

    $ composer require "plancke/hypixel-php=^1.0.0"

## Usage

To interact with the API you need an API key, you can get a key by doing "/api" on the Hypixel Network.

```PHP
$HypixelPHP = new HypixelPHP('API_KEY');

// you can override modules, not required
$HypixelPHP->setCacheHandler(...);
$HypixelPHP->setLogger(...);
$HypixelPHP->setFetcher(...);
```

## Old Version

You can find the old 1 file version in the [old branch](https://github.com/Plancke/hypixel-php/tree/old). 