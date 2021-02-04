Rabbit Hole
======================

Rabbit Hole is a module that adds the ability to control what should happen when
an entity such as a content item, taxonomy term, or user account is being
viewed at its own page.

Perhaps you have a content type that never should be displayed on its own page,
like an image content type that's displayed in a carousel. Rabbit Hole can
prevent this node from being accessible on its own page, through a path such
as `node/xx`.

## Options

This works by providing multiple options to control what should happen when it
is being viewed at its own page. You have the ability to

 - Deliver an access denied page.
 - Deliver a page not found page.
 - Issue a page redirect to any path or external url, including tokens
   if desired.
 - Display the page as usual.

This is configurable (for example in the content type, taxonomy term, and
user account configuration pages). There is also a permission that
allows certain roles override Rabbit Hole completely.

## Other options

If you just need a simple way to prevent node content of a certain type from
being displayed, you may not need Rabbit Hole. Backdrop core now provides a
"Hide path display" option under the "Display settings" tab when configuring
a content type. This causes a "Page not found" notice to display for users 
without a special permission to "View hidden paths."


Installation
------------

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

Instructions
------------

Please view and contribute to the [Wiki](https://github.com/backdrop-contrib/rabbit_hole/wiki) for further instructions.

Issues
------

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/rabbit_hole/issues)

Current Maintainers
-------------------

- [Laryn Kragt Bakker](https://github.com/laryn/), [CEDC.org](https://CEDC.org) 

Credits
-------

- Ported to Backdrop by [Herb v/d Dool](https://github.com/herbdool) and [Laryn Kragt Bakker](https://github.com/laryn/), [CEDC.org](https://CEDC.org)
- Maintained for Drupal by [shumushin](https://www.drupal.org/u/shumushin), [olofjohansson](https://www.drupal.org/u/olofjohansson), and [Dylan Donkersgoed](https://www.drupal.org/u/dylan-donkersgoed)
- Support for Drupal by [Odd Hill](http://www.oddhill.se/)


License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
