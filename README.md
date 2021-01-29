# js-linux-modified
A modified version of Fabrice Bellard's JSLinux; needed to run a couple ae27ff tools.

## Modifications applied by this fork
 - JSLinux loader modified to allow setting startup parameters by another script instead of only from page address/query (more modular)
 - Upload progress code is currently disabled until more modular code can be added.
 - File table has been modified to indicate mounted files at reserved addresses
 - File system requests are caught by a PHP loader which redirects reserved addresses to mounted files.
