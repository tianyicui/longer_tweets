The line `alias v='vim'` has been in my `.bashrc` for a long time, but I've been always typing `vim` in terminal hundreds of times a day (which actually opens MacVim).

So the solution is, in `.bashrc`:

    alias v='mvim'
    alias vim="echo use 'v' instead !!! # "

Yes I'll *force* myself to use a more convenient way.

Future plans: 

* disable `:w` and `:q` in order to force me to use `command-S` and `command-W` in MacVim
* disable keys like `left-shift-A` and `left-shift-1` ...

This is just **geek's self-discipline**.