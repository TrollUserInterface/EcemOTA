# EcemUI OTA

## To Add Your Device

Add this line to your ecem.mk

[CODE]
# Official
ECEM_BUILD_TYPE := OFFICIAL
[/CODE]

Create a destination CMUpdater/res/values in your device tree overlay folder

And add this xml file into that folder

* [JSON](https://gist.github.com/Mbtt107/247717ca23a4abf6358fb1da8b2a9e72)

And make proper changes.

Change branch and repo name as your wish

For example:

https://gist.github.com/Mbtt107/cb3db466fe2727b0e1cd927af5a646f3

### Tips

Make a proper pull request after making changes
