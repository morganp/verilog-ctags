CTAGS for Verilog
==

.ctags
--

Defines keywords in verilog to allow ctags to build for verilog files.

make_ctags
--

Run from top level verilog folder and will recursively search for verilog files and build the ctags.


Install CTAGS
--

on OS X with homebrew

    brew install ctags

Browsing Code with CTAGS in VIM
--

When on a module name to browse to source `ctrl+]` or `ctrl left click`.

To go back `ctrl+T` or `ctrl right click`.

If using the [verilog-systemveriloglanguage file by vhda](https://github.com/vhda/verilog_systemverilog.vim) then some special functions have been created:

    :FollowInstance
    :FollowPort
    :GotoInstanceStart

Follow instance works like `ctrl+T` but does nt require the caret to be on the module name
