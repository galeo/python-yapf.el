python-yapf.el
==================

Format Python code according to the `pep8` or `google` style using the [yapf](https://github.com/google/yapf) formatter in Emacs.


Installation
--------------

First, install Python **yapf** package with **pip**:

```sh
pip install -U yapf
```

Then, copy `python-yapf.el` to your load-path and add to your `~/.emacs`:

```elisp
(require 'python-yapf)
```

Usage
--------

Three commands are supplied to format python code:

* `python-yapf-region`: *Format the code of the region or the buffer if no region selected.*
* `python-yapf-file`: *Format a file(by default the one opened in current buffer).*
* `python-yapf-directory`: *Search and format .py files in a directory.*

Run them interactively:

```
M-x python-yapf-* RET
```

Or set any key bindings you like.


Attention
------------

Currently, *YAPF* is in alpha stage(buggy) and may change often in the released version, many features are required to enhance the code formatting. When you format code files, please *remember to make backups*.


Feedback
-----------

Bugfix or suggestions/improvements [welcome](https://github.com/galeo/python-yapf.el/issues)!
