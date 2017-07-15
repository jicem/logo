"# logo" 

The logo folder needs to go in the root wiki directory (the same folder as LocalSettings.php)

Images in the rotation need to go into the logo folder

In LocalSettings.php, you need to set $wgLogo to the location of logo/index.php

On the WUW it looks like this:

$wgLogo = 'http://wuw.cu.cc/wiki/logo/index.php';

Credit to Sam Horn (https://github.com/clamburger) for most of the code.