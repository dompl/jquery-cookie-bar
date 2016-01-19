Forked
http://www.primebox.co.uk/projects/jquery-cookiebar/ 


jQuery CookieBar example

This is an example showing the cookie bar's default settings.

Ensure you have jQuery, jQuery CookieBar and jQuery CookieBar's CSS uploaded to your website and linked in the header of your website

<link rel="stylesheet" type="text/css" href="/css-folder/jquery.cookiebar.css" />
	<script type="text/javascript" src="/scripts-folder/jquery-1.7.1.min.js"></script>
 <script type="text/javascript" src="/scripts-folder/jquery.cookiebar.js"></script> 

Make sure you then include the following line of code within $(document).ready():

$.cookieBar(); 

If you find that the bar appears even after accepting/declining, make sure "forceShow" is set to false.

For more information about PrimeBox's CookieBar plugin, go to www.primebox.co.uk/projects/cookie-bar/.
