# Kohana 3.3 Log Viewer module
## A Kohana module for exploring log files

### Disclaimer

This module forks the one from https://github.com/ajaxray and patches it up to actually work...

### Installation:

1. Download this module and add the **logviewer** folder it to your `MODPATH`
2. Enable it in the `bootstrap` file
3. Go to _http://your-app-root/logs_
4. You are done! 

![Kohana Log Viewer interface](http://ajaxray.com/files/log_formatted.png "Kohana Log Viewer interface")

### How to use?

It's completely self explanatory. Here are some points for quick refs - 

- All months are listed on top nav. e.g, **2011/11**
- Left sidebar has a list of available log files in selected month
- If not specified, today's (current month and day) log file will be displayed
- If you want to see a fresh log for next call, just delete today's file. Kohana will generate it and add 
- You can use *Level* listbox for filtering by log levels.

### Notes:

- _http://your-app-root/logs_ should display the log reports interface. If it don't, please check the routing in `modules/logviewer/init.php` 
- If you change the folder name, change the paths in `modules/logviewer/views/logs/layout.php` accordingly.
- If you want to improve, please fork and participate. 
- If you've a suggestion or found a bug, please let me know at - anisniit(at)gmail.com
- BE CAREFUL ABOUT USING ON PRODUCTION!


