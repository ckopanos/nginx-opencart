nginx-opencart
==============

Nginx configuration file for opencart

This is configuration file for Nginx to be used for an opencart based eshop.
Most lines are commented so you will find your way around.

Use it as a base for your own setup and adjust to your needs.

On my part i prefer to leave only the catalog/view, admin/view
and images folders on the root web folder, as well as the index.php
file for the main web site and the admin section, and have everything else like
system/, and the rest of the files in catalog/ and admin/ out of the root folder.
This requires of course a small modification in the config.php file and admin/config.php
files as well as the relevant index.php files.


