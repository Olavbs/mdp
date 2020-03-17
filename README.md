# mdp
#### A simple markdown previewer
Using [pandoc](https://pandoc.org/), [inotify-tools](https://github.com/inotify-tools/inotify-tools/wiki) and [nweb](https://aur.archlinux.org/packages/nweb/) to provide a live markdown preview  
Make sure you have these tools installed.

Usage: `mdp <file>`  
The preview will only update on save, so running `mdp` alone won't preview your file, you will have to save the file to update the preview.

`mdp-server` needs to be in the same directory as the `mdp` script.  
I recommend copying both `mdp-server` and `mdp` to a folder in your `$PATH` to run `mdp` from anywhere.  
A little hacky, but i couldn't be bothered.
