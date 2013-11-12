CodeMirror-VimSleek
===================

This is a fork of the original CodeMirror Vim mode that provides [vim-seek] (https://github.com/goldfeld/vim-seek) among other things that (I reckon) improve the Vim experience on CodeMirror. It might drive vintage Vim users nuts, though.

This repo will stay updated with upstream master and work with the latest version of CodeMirror.


## Features

* [vim-seek] (https://github.com/goldfeld/vim-seek) with `s` & `S`. `;` and `,` repeats seeking in forward/backward direction
* Removes `f` & `F` (adding them back should be very simple though), and replaces them with pagewise [vim-seek] (https://github.com/goldfeld/vim-seek)  (like seek, but searches the entire screen). Works with `;` and `,` too.
* `t` & `T` now does tail seek like `x` in [vim-seek] (https://github.com/goldfeld/vim-seek).
* Working `g` flag in substitute (Will commit to upstream).
* Yank that does not copy extra character after the cursor. (Will commmit to upstream).
* Copies to/Pastes from system clipboard when no register is specified. (Only works in node-webkit based editors, will silently fail otherwise)
* Maps `U` to redo. It used to map to do nothing.
* Maps `C-k` & `C-j` to page-up/down. They used to do nothing.
* Maps `C--` & `C-+` to walk backward/forward in jumplist.
* Moar in development

## Credits

All Credits to [goldfeld] (https://github.com/goldfeld/) who created the awesome [vim-seek] (https://github.com/goldfeld/vim-seek) extension.

## License

Considering that this is just a <100 LoC diff from the original CodeMirror Vim mode, any effort to restrict the copyright would be ridiculous. Do whatever you wanna do with it.
