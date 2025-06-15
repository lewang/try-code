## Installation:

    (autoload 'try-code "try-code"  nil t)
    (global-set-key (kbd "C-?") 'try-code)


## Commentary:

**Scenario**: you want to try an alternative implementation of a region while
keeping the original for comparison. This happens on the fly, before you're
ready to commit to VC, etc.

1. Select lines.
2. C-?
3. (optional) C-y (yank original implementation)
4. make changes as required
5. press C-? again

When you reinvoke the function, you can choose which implementation to
keep.

Try it out; bug reports are welcome.

