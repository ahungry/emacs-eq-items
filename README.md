# eq-items
Easily query p99 item information in emacs!

## Installation
To install, clone the repository via:

```
cd ~/.emacs.d
git clone https://github.com/ahungry/emacs-eq-items.git eq-items
```

Then, make sure to add the following to your ~/.emacs:
### Using load-theme
```lisp
(add-to-list 'load-path "~/.emacs.d/eq-items/")
(require 'eq-items)
```
Make sure to `M-x package-install helm' if you don't have it yet (this makes
extensive use of it)!


### Using eq-items.el

```lisp
M-x eq-items/search-wiki ;; Will invoke a search on the wiki
M-x eq-items/search-buyers ;; Will invoke a search for all buyers
M-x eq-items/search-sellers ;; Will invoke a search for all sellers
M-x eq-items/search-all ;; Will perform all 3 searches at once
```

## TODO/Yet to come
An actual emacs major-mode for fast key binds, including logging
of your buying and selling to build a history of item transactions.

## Different sample shots
This is what it could look like (depending on your emacs theme
settings of course!)

### Sample screenshot
![Screenshot Sample](http://ahungry.com/img/emacs-eq-items/sample.png)

## License
GPLv3
