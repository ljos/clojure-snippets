# clojure-snippets
Snippets for yasnippet-mode in emacs for faster editing.

## How to use
  + Install [yasnippet](https://github.com/capitaomorte/yasnippet)
  + `git clone https://github.com/ljos/clojure-snippets.git
  ~/.emacs.d/snippets/clojure-mode` 

If you have auto-complete installed add 

    (add-hook 'clojure-mode-hook '(lambda () (setq ac-sources (cons ac-source-yasnippet ac-sources))))

to emacs config to get snippets on the top of the auto-complete menu.
