YouTubeWall
*********

### ABOUT
YouTubeWall is a web video gallery script, free for private and commercial use, and developed by Kris, on the basis of Pagemap Premium Portfolios in Germany

Demo kris : https://xoofoo.org/demo/youtubewall/

### SYSTEM REQUIREMENTS
- Apache Webserver (recommended) or IIS
- PHP version 4.3 or greater

### INSTALLATION
- Download a copy from https://github.com/krisxoofoo/YouTubeWall/zipball/master and unpack it on your webserver.
- Per line, add video code and description (separated by a semicolon) in videos.txt, 
- Open your web browser and go to the script at http://www.yourdomain.com/index.php
- That's it. If you want to configure the script see next chapters.

### CONFIGURATION
You can change the look and feel of the YouTubeWall in many ways.
Create a config.ini in the same directory as YouTubeWall

### EMBEDDING
If you want to include the script (index.php) in a custom PHP file set Config Tag [Embedded Script'] to "on" and use $set['script name'] in your script to define the path to the YouTubeWall script. You can optional define a root path for config file and default images dir with $set['script dir'].

### TROUBLESHOOTING
If you are having problems installing or using YouTubeWall, please post issue here: https://github.com/krisxoofoo/YouTubeWall/issues

### LEGAL INFORMATION
Basis code is originally written by Nico Wenig (Pagemap Premium Portfolios).

The software is provieded as is, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from
out of or in connectioin with the software or the use of other dealings in the software.

### TERMS OF USE:
You are allows to:
- Use for private and commercial
- Copy and distribute the script
- Customize the function and design

You are NOT allowed to:
- Claim the script as your own
- Sale parts of the script

### CREDITS:
- Nico Wenig for initial code
- Tory Lawson for YouTube Gallery
- V Song for Page navigation
- Rafael Paulino for cache system
- jQuery Team
- Brandon Aaron for jQuery-mousewheel
- Yair Even for PhotoBox
