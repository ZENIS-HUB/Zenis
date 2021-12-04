Exporting the Wordpress Site as a Static Website
First, we must install a plugin that will allow us to export the site’s HTML, CSS, and JavaScript files. In the Wordpress site’s admin panel go to “Plugins” => “Add New” on the left-hand side menu.

wordpress1

Next, search for the plugin called “WP2Static”, download it and activate it.

wordpress2

The plugin will create a new menu option on the left-hand side menu name “W2PStatic”.When clicking on it, we must fill the form as shown in the image below by selecting the “Zip archive (.zip)” in the dropdown menu and checking the “Allow offline usage” option. This will create a zip archive with no preset root path which will render the site’s paths compatible with the IPFS deployment. After that, click “Start static site export”, wait until the export is done, and download the file via the “Download ZIP” button.

wordpress3

Finally, the downloaded file can be unzipped. The folder contains the totality of the Wordpress Site.
