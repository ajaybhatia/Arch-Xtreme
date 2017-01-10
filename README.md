# archxtreme-iso

This is the 64-bit source for the archxtreme iso.

How to use:
- To download use:  git clone https://github.com/ajaybhatia/archxtreme-iso
- Move the customrepo folder to your home folder

Change the permission of the archxtreme-iso to root
i.e. sudo chown -R root:root archxtreme-iso

As root open ~/archxtreme-iso/pacman.conf and change to Server=file:///home/your_user_name/customrepo/$arch (near the botton)

Navigate to ~/customrepo/x86_64
- In a terminal type:
repo-add customrepo.db.tar.gz *.tar.xz

Be sure to edit/build as root or sudo

Feel free to edit, add/remove packages, or fork, etc. as you see fit.
