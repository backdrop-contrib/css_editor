Custom CSS Editor
======================

This module allows administrators to customize a theme's CSS through
the browser, using a rich text editor with syntax highlighting and
live preview.

The module has just one option in its configuration page. You can choose
which themes can use the custom CSS feature. So, on the settings page
of each theme enabled to use this feature, a textarea field wiil be made
available where the admin can enter custom CSS code. The admin can choose to
use a plain textarea or an editor with syntax highlighting (default).
The changes can be previewed live while being entered. This can be disabled
as well (default is enabled). This feature can be enabled and applied one or
more themes on the same site and all options can be previewed live. Not only the
default selection. The custom CSS code is injected after all the other CSS in
the theme loads.

Check [this video](http://ca.ios.ba/files/drupal/csseditor.ogv) to understand
better how it works.

Requirements
------------

This module requires that the following modules are also enabled:

 * None

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Visit the configuration page under Administration > Configuration >User
  Interface > CSS Editor (admin/config/user-interface/css-editor) and enter
  the required information.

- Any additional steps.
  Select one or more themes to implement the CSS Editor.

Documentation
-------------

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/css_editor/wiki/Documentation.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/css_editor/issues.

Current Maintainers
-------------------

- [Justin Christoffersen](https://github.com/larsdesigns).
- [Jen Lampton](https://github.com/jenlampton).
- Seeking additional maintainers.

Credits
-------

- Ported to Backdrop CMS by
  [Justin Christoffersen](https://github.com/larsdesigns).
- Originally written for Drupal by
  [Caio Almeida](https://github.com/caiosba).
- Backdrop port sponsored by
  [Jeneration Web Development](https://www.jenerationweb.com/).
- Drupal module Sponsored by [Meedan](http://meedan.org).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
