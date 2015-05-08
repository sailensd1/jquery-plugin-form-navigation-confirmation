Copyright (c) 2009 Law Ding Yong

Licensed under the MIT license:
http://www.opensource.org/licenses/mit-license.php

This is a jQuery Plugin that handles onchange of form input(s) to toggle on and off of window.onbeforeunload event.

Form input(s) includes all type of text, textarea, password, radio, checkbox and file.
Form input(s) types of submit and button will trigger off navigation confirmation event.

Users are able to configure the custom return message by onbeforeunload event.

Browser Compatibility :
IE 6.0, 7.0, 8.0;
Firefox 2.0+;
Safari 3+;
Opera 9+;
Chrome 1+;



Use Example:

$("#YourForm").FormNavigate("YourMessage");



Version changes:

Version 1.1 (thanks to kurund)
> - Corrected bug that do not handle Back button navigation
> - Corrected textarea do not prompt confirmation in MAC.