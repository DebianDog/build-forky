## build-forky
### Create a Debian forky minimal live system similar to 'DebianDog'

This works very similar as the 'mklive-forky' script:    
https://forum.puppylinux.com/viewtopic.php?t=15776     
except that it's very much simplified.

Support for "xlibre" install (replacement of xorg). NOTE: only for amd64      
Run with .conf file *-xlibre.conf, e.g `./build-forky configs-forky/lxqt-full-xlibre.conf`


`fredx181, 2025-11-03, stripped down version of mklive-forky`    
`supports only .conf files as an argument, e.g. ./build-forky /path/to/myconfig.conf`    
`no dependency on yad (as this has no GUI), no dependency on files to download from the 'MakeLive' repository.`    


`Usage: ./build-forky <config_file> (presets are in configs-forky) `   
 `-help show this help `   
 `Example using one of the preset config files:`    
 `./build-forky configs-forky/lxqt-full.conf`
 `Example using one of the preset config files to install xlibre rather than xorg:`       
 `./build-forky configs-forky/lxqt-full-xlibre.conf`       
 `Example with custom config file:`    
 `./build-forky /path/to/my.conf `   

 
