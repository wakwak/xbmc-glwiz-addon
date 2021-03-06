# GLArab XBMC plugin #

## Arabic Add-on Repository ##
GLArab is now part of _hadynz's_ Arabic add-on repository, install it via the repository to take advantage of automatic updates and other great add-ons _hadynz_ puts together.

https://github.com/hadynz/repository.arabic.xbmc-addons

## F.A.Q. ##

---

  * **Why are none of the channels working?**
The GLArab plugin requires that you install the GLArab proxy software on your local machine to be able to
view their streams. The proxy software is available for both Windows and Mac from the main
http://www.glarab.com website.


  * **Can I use this plugin with XBMC on the Apple TV, Raspberry Pi, ...?**
Yes and No.

As mentioned in the previous FAQ, GLArab requires a proxy to be downloaded and installed on a machine that
would like to stream GLArab channels. A proxy cannot be installed on Apple TV.

To get around this problem, simply do the following:

  1. Install the GLAraby proxy software from the main website on a Windows/Mac machine
  1. Configure the GLArab plugin in your Apple TV use a proxy. In the configuration of the plugin, set the proxy field to the IP address of the computer in your network that has the proxy installed.

The above solution will require that your machine with the GLArab proxy software installed to always be on.

  * **I have the proxy installed on a Windows machine and have configured the IP address in plugin settings, it still doesn't work.**

  1. On Windows, get _glarab\_http\_proxy-1.4.0.5571.exe._ Newer versions don't support non-local connections according to some users.
  1. Make sure your firewall allows incoming TCP connections on port 4500.
