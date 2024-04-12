# NoLua.vim may contain LUA

ignore me: [Bumper Pool](/)

This is my old init.vim file before trying to convert to lua. I am keeping it here because it's functional for me for vimwiki and time tracking on projects and tasks with vimtask, timewarrior, taskwarrior, and related tools I have been using for a few years.


![Screenshot from 2024-04-11 21-28-10](https://github.com/badlandz/nolua.vim/assets/30945171/e888625b-662d-4dd1-a3bd-c6029f480e52)
There are many requirements for setup, and the documentation for setup can be found by the plugin maintainers. I will provide more information when I have time.



## Test Area

This area can be edited and played with in vim, to make sure the plugins are working:

* [ ] This is task 1  #6ef6b5fa
* [ ] This is task 2  #3625486d
		* [ ] Do this before task 2  #10f58606
		### Format Issue displaying in GitHub

This links to a [New README](new/README.md) created using the editor, you will create one on your system when you use it.


# BUGS


## NIXOS
Ok, not working in my nix build because I don't have python installed... the test below seemed to show, I don't have python on that box.
```
nvim -u ~/github/badlandz/nolua.vim/init.vim README.md
pip3 install tasklib pynvim tasklib vimwiki
which python
```

## VIM
This thing still is a neovim init, even if it's not lua, it chokes in regular "vim" instead of nvim. Need to clean this up if I can, make it tighter.
