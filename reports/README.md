# Racktables custom report plugin                                                                                                                                          
This is an additional plugin for RackTables, based on the work of 
Mogilowski Sebastian <sebastian@mogilowski.net>


## Installation

1) Copy the files in the /reports/ (THIS) folder to your RackTables plugins
   installation ( '/path/to/racktables/plugins/ ).

2) Copy the CSS and JS files to the corresponding folders:
   mkdir -p '/path/to/racktables/wwwroot/{css,js}/report/'
   cp -v 'css/style.css' '/path/to/racktables/wwwroot/css/report/style.css'
   cp -v "js/*" '/path/to/racktables/wwwroot/js/report/'

3) Activate the plugin via the 'Configuration' => 'Plugins' menu.

4) Depending on where you copied the CSS and JS files in step 2, you might 
   want to adjust the configuration variables in 
   'Configuration' => 'User interface':
   a) REPORTS_CSS_PATH => defaults to 'css/report' (NO trailing slashes)
   b) REPORTS_JS_PATH  => defaults to 'js/report'  (NO trailing slashes)

5) You might also want to enable/disable the MAC(s) column for your switch report
   via 'Configuration' => 'User interface':
   a) REPORTS_SHOW_MAC_FOR_SWITCHES => defaults to 'yes'

