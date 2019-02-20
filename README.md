# vim-searchindex

This plugin shows how many times does a search pattern occur in the current
buffer. After each search, it displays total number of matches, as well as the
index of a current match, in the command line:

<img src="https://raw.githubusercontent.com/google/vim-searchindex/master/vim-searchindex.gif" width="90%">

While navigating between matches it centers the current match in the window and unfolds appropriately.

You can also press `g/` to display search index for the last search term at the
current cursor position.

That's it! The plugin is as simple and unobtrusive as possible. It works out of
the box with all built-in search commands, and stays fast even on huge files
thanks to caching. For full documentation (including extensibility and
configuration options), see `:help searchindex`.

