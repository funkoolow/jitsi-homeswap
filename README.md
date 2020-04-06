# jitsi-homeswap
quick and dirty homepage swap for jitsimeet homepage (https://www.jitsi.org): css + js + html only - no htaccess, react or system configs editing needed!
the concept behind homepageswap is to hide all the original divs in homepage via css and include a basic html page with a field which redirects the user to the meeting page :)

how to:
1) copy homeswap.html and css/homeswap.css in your ```/usr/share/jitsi-meet/``` base folder
2) in index.html include the css file with ```<link rel="stylesheet" href="css/homeswap.css">``` in head section
3) in index.html add ```<!--#include virtual="homeswap.html" -->``` after ```<div id="react"></div>```
4) reload your jitsi-meet homepage :)

feel free to tweak your style: nothing more than basic js, html and css knowledge is needed!
IMPORTANT NOTE: I'm a total jitsinub, just installed on ubuntu-18.04 server setup from official repo, without any significant modification, so I really don't know if this may break something somehow!
use at your own risk!
