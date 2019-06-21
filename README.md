# code-eiditor
# Sublime all Package

https://packagecontrol.io/installation
Sublime Text 3 (Version 3.2.1, Build 3207)
INSTALLATION
Simple
The simplest method of installation is through the Sublime Text console. The console is accessed via the ctrl+` shortcut or the View > Show Console menu. Once open, paste the appropriate Python code for your version of Sublime Text into the console.


import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)



Manual
If for some reason the console installation instructions do not work for you (such as having a proxy on your network), perform the following steps to manually install Package Control:

1.Click the Preferences > Browse Packages… menu
2.Browse up a folder and then into the Installed Packages/ folder
3.Download Package Control.sublime-package and copy it into the Installed Packages/ directory
4.Restart Sublime Text


Package Control
Emmet
AutoFileName
AutoSave
Advanced New File
Beautify
Browser Sync
A File Icon
Side​Bar​Enhancements
Bracket​Highlighter
Sublime​Linter
Sublime​Code​Intel
HTML5
Alignment
Color​Picker
Sass
Matrialize
