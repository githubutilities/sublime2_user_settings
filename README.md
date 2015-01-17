#sublime2_user_settings 
[![Build Status](https://travis-ci.org/matej/MBProgressHUD.png)](https://travis-ci.org/matej/MBProgressHUD)

my personal user settings for sublime text 2

## Requirements

this require sublime text installed

## Get Started
1. install package control
The console is accessed via the ctrl+` shortcut or the View > Show Console menu. Once open, paste the appropriate Python code for your version of Sublime Text into the console.
```python
import urllib2,os,hashlib; h = '2deb499853c4371624f5a07e27c334aa' + 'bf8c4e67d14fb0525ba4f89698a6d7e1'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); os.makedirs( ipp ) if not os.path.exists(ipp) else None; urllib2.install_opener( urllib2.build_opener( urllib2.ProxyHandler()) ); by = urllib2.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); open( os.path.join( ipp, pf), 'wb' ).write(by) if dh == h else None; print('Error validating download (got %s instead of %s), please try manual install' % (dh, h) if dh != h else 'Please restart Sublime Text to finish installation')
```

2. follow the environment specific configuration

### Mac OS
1. `https://github.com/githubutilities/sublime2_user_settings.git` the repository
2. simlink the directory to ~/Library/Application Support/Sublime Text 2/Packages/User
3. restart sublime and it will automatically start install the package

