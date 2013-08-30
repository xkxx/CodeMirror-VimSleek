CodeMirror-VimSleek
===================

This is a fork of the original CodeMirror Vim mode that provides vim-seek among other things that (allegedly) improves Vim experience on CodeMirror. It might drive vintage Vim users nuts, though.

## Features

* vim-seek with `s` & `S`. `;` and `,` repeats seeking in forward/backward direction
* Removes `f` & `F` (adding them back should be very simple though), and replaces them with pagewise seek (like seek, but searches the entire screen). Works with `;` and `,` too.
* `t` & `T` now does tail seek like `x` in vim-seek.
* Working `g` flag in substitute (Will commit to upstream).
* Maps `U` to redo. It used to map to do nothing.
* Maps `C-k` & `C-j` to page-up/down. They used to do nothing.
* Moar in development

This repo will stay updated with upstream master and works with latest version of CodeMirror.
