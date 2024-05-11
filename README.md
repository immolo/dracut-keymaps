# dracut-keymaps
A dracut hook to allow a user to select their required keymap at boot time.

# Credits
Orginal code base is from the Genkernel project - https://github.com/gentoo/genkernel

Special thanks to Christopher Fore for doing the orginal work to find all the needed files for this project.

# Usage
When building with dracut the arguements "-i /lib/keymaps /lib/keymaps -I busybox" need to added.

At boot time "dokeymap" needs to be added to the boot cmdline for it to be called.
