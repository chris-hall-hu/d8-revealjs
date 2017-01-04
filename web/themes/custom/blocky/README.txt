
ABOUT BLOCKY
------------

Blocky is a theme for Drupal 8, using Stable as a base theme (see below) with
Twig block markup added to a number of templates, allowing parent templates to
be extended http://twig.sensiolabs.org/doc/tags/extends.html by themes 
that sub-theme Blocky.

Twig block markup allows for more selective override of parent templates in
sub-themes via extension as opposed to making an entire new copy of the parent
template (which can often lead to a lot of repeated work if a small part of the 
parent is subsequently altered).

To use Blocky as your base theme you can set the base theme in your theme's 
.info.yml file:
  base theme: blocky

Blocky may also be copied and used as an example of Twig block markup and
a basis for alternative base themes.

ABOUT STABLE
------------

Stable is the default base theme; it provides minimal markup and very few
CSS classes.

Stable allows core markup and styling to evolve by functioning as a backwards
compatibility layer for themes against changes to core markup and CSS. If you
browse Stable's contents, you will find copies of all the Twig templates and
CSS files provided by core.

Stable will be used as the base theme if no base theme is set in a theme's
.info.yml file.

ABOUT DRUPAL THEMING
--------------------

For more information, see Drupal.org's theming guide.
https://www.drupal.org/theme-guide/8
