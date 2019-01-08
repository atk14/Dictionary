Dictionary
==========

Dictionary implementation used in the ATK14 Framework

Basic usage
-----------

    $dictionary = new Dictionary([
      "key1" => "val1",
      "key2" => "val2",
      "key3" => null, 
    ]);

    $dictionary->getValue("key1"); // "val1"
    $dictionary->getValue("key3"); // null
    $dictionary->getValue("key4"); // null

    $dictionary["key1"]; // "val1"
    $dictionary["key3"]; // null
    $dictionary["key4"]; // null

    $dict->defined("key1")); // true
    $dict->defined("key3")); // false
    $dict->defined("key4")); // false

    $dict->keyPresents("key3")); // true
    $dict->keyPresents("key4")); // false

Installation
------------

Use the Composer to install Dictionary

    cd path/to/your/project/
    composer require atk14/dictionary

Licence
-------

Dictionary is free software distributed [under the terms of the MIT license](http://www.opensource.org/licenses/mit-license)

<!-- vim: et:ts=2 -->
