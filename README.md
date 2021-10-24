# get-waterfox
Installs Waterfox on every Linux machine, as simple as possible!
This application is intended for network admins.
But can also be used for private use without problems.

# Install this tool
If you wish to install my tool (not needed, it works perfectly without beeing installed), just run: <br>
`$ sudo ./get-waterfox-install` <br>

# How to use it
First thing you have to do is to run the init: <br>
`$ sudo get-waterfox init` <br>
This will create the folders `/usr/share/waterfox` & `/usr/share/waterfox-data`, you only have to execute it once. <br>
<br>
Then you can download Waterfox from the official source: <br>
`$ get-waterfox download` <br>
With testrun you can check whether the new version works (optional) <br>
`$ get-waterfox testrun` <br>
After that, we are ready to install it: <br>
`$ sudo get-waterfox install` <br>

# Update Waterfox
If you wish to update your installed Waterfox, just run:<br>
`$ sudo get-waterfox update` <br><br>
If you only wish to check if there is an update for waterfox: <br>
`$ sudo get-waterfox checkupdate` <br>

# Target Waterfox
You can choose if you want to use Waterfox __Classic__ or __G4__<br>
`$ get-waterfox target classic` <br>
or <br>
`$ get-waterfox target G4`<br>

# Cleanup your cache
If you wish to remove the cache copy of the Waterfox tarball in `/usr/share/waterfox-data`, just run:<br>
`$ sudo get-waterfox cleanup` <br>

# Remove Waterfox
If you wish to remove Waterfox, just run:<br>
`$ sudo get-waterfox remove` <br>
This will remove `/usr/share/waterfox` & `/usr/share/waterfox-data` too. If you want to install Waterfox again, you need to reexecute `init` first. <br>

# Remove this tool
If you wish to remove this tool, just run:<br>
`$ sudo ./get-waterfox-remove` <br>

# Flags
<table>
  <tr>
    <td>init</td> <td>-I</td>
  </tr>  
  <tr>
    <td>target</td> <td>-t</td>
  </tr>  
  <tr>
    <td>showtarget</td> <td>-s</td>
  </tr>  
  <tr>
    <td>download</td> <td>-d</td>
  </tr>
  <tr>
    <td>testrun</td> <td>-T</td>
  </tr>  
  <tr>
    <td>install</td> <td>-i</td>
  </tr>  
  <tr>
    <td>cleanup</td> <td>-C</td>
  </tr>  
  <tr>
    <td>checkupdate</td> <td>-c</td>
  </tr>  
  <tr>
    <td>version</td> <td>-v</td>
  </tr>  
  <tr>
    <td>remove</td> <td>-r</td>
  </tr>
</table>

# Personal config
This tool will not touch any config file you got in `/home/youraccound/.waterfox`! <br>
Not even on `$ sudo get-waterfox remove` or `$ sudo ./get-waterfox-remove`.

# License
![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)

This program is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
