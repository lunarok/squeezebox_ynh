squeezebox_ynh
==============

***Be aware that this app for now only configure a reverse proxy to access your Squeezebox installation.***

  Yunohost App to add Squeezebox (a web frontend to manage multi-rooms music)

**Status** : The app can be used, it's working. But will not automaticly install Squeezebox, you must have a functionnal Squeezebox before (on the Yunhost server or other server)

It's creating a reverse proxy configuration. Find information on Yunohost wiki for installation/configuration of Squeezebox to work behind a Reverse Proxy

**TODO : install Squeezebox if the server choosen is localhost**

**IMPORTANT : I have been able to use Squeezebox only on a root URL for a domain, using it in a location is not working with nginx. If you have success in it, please share the rules and I will update this app**

More information about Squeezebox :
http://wiki.slimdevices.com/index.php/Main_Page

More information about the Yunohost App :
https://doc.yunohost.org/app_squeezebox
