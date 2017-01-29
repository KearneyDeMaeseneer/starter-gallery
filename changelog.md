#Change Log

Team membership:  Jonathan De Maeseneer (Captain) & Matt Kearney (Mate)  
Team conventions: Allman notation, markdown for changelog  
Changelog format: [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 

## *Version 1.0*

Release Date: Jan 24, 2017

## New Components

Converted from static html to CodeIgniter:
- setup views and controllers
- fixed the nav bar to work with CI

Converted from trivial to basic website:

- application/views/template.php: pagetitle, content
- public/index.html: css root changed
- views/welcome.php: kept "meat"
- application/core/MY_Controller: changed title
- application/controllers/About.php: used base ctrler rendering
- application/controllers/Gallery.php: used base ctrler rendering
- application/controllers/Welcome.php: used base ctrler rendering

Converted from Basic CI site to Good CI site:

- .gitignore (3)
- application/config/autoload.php (6)
- application/controllers/Gallery.php (22)
- application/controllers/Welcome.php (22)
- application/models/Images.php (25)
- application/views/_cell.php (15)
- application/views/about.php (36)
- application/views/gallery.php (105)
- application/views/welcome.php (14)
