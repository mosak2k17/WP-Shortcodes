# WP-Shortcodes
shortcodes for wordpress

use this shortcode sample:

ex:1 [loop category="news" query="" pagination="false"]
ex:2 [loop category="news" query="showposts=10" pagination="true"]

for custom template file use this code:
<?php echo do_shortcode('[loop category="news" query="showposts=5" pagination="true"]');?>
