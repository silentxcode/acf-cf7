Contact Form 7 add-on for ACF plugin (WP)
=======

ACF-CF7 is an add-on for the ACF (<a href="http://www.advancedcustomfields.com">Advanced Custom Fields</a>) Wordpress plugin that lets you assign one or more CF7 (<a href="http://contactform7.com/">Contact Form 7</a>) contact forms to a post.

ACF-CF7 displays a simple drop down/multiple select form field in a custom meta box.

Screenshots
=======
<img src="http://desmond.imageshack.us/Himg838/scaled.php?server=838&filename=acfcf71.jpg&res=landing">

Setting up ACF-CF7

<img src="http://desmond.imageshack.us/Himg210/scaled.php?server=210&filename=acfcf72.jpg&res=landing">

ACF-CF7 multiple select with forms disabled

<img src="http://desmond.imageshack.us/Himg580/scaled.php?server=580&filename=acfcf73.jpg&res=landing">

Using ACF-CF7 with the flexible content field


Installation
=======

1. Copy 'acf-cf7.php' to your theme:
  <a href="https://github.com/taylormsj/acf-cf7/blob/master/acf-cf7.php">https://github.com/taylormsj/acf-cf7/blob/master/acf-cf7.php</a>

2. Register the field:

<pre><code>  if(function_exists ('register_field')){
    register_field('acf_cf7_field', 'link-to-file/acf-cf7.php');
  }
</pre></code>
 
Returned Value
=======

<b>Single form:</b> Returns a String containing the form's markup

<b>Multiple forms:</b> Returns an Array of Strings containging the form's markup

About
=======

Version 1.0

Written by Taylor Mitchell-St.Joseph - <a href="mailto:taylor.mitchellstjoseph@gmail.com">taylor.mitchellstjoseph@gmail.com</a>

Credits
=======

Based on code written for <a href="https://github.com/stormuk/Gravity-Forms-ACF-Field">Gravity Forms Field</a> by Adam Pope
