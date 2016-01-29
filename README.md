## netboot.xyz-custom

### EXPERIMENTAL

Fork me!  This repo will allow you to create custom menus within netboot.xyz.
It works by using your github user name that you input and chains to this url:

    https://raw.githubusercontent.com/${github_user}/netboot.xyz-custom/master/custom.ipxe

Once forked, you can edit the menu as much as you want.  You can compile the iPXE image to
set the github_user name early on so that you're github user name is set ahead of time and
will automatically display your custom submenu on boot.

If you are new to iPXE scripting, take a look at custom.ipxe.example and build up from that.

