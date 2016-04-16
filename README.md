# dark-mint-theme [![MELPA](https://melpa.org/packages/dark-mint-theme-badge.svg)](https://melpa.org/#/dark-mint-theme)

A dark & fresh looking theme for emacs

![screen shot 2016-02-15 at 5 27 23 pm](https://cloud.githubusercontent.com/assets/3979753/13062113/14e6c9a2-d40a-11e5-9d9f-3cb5697881ea.png)

![screen shot 2016-02-14 at 10 40 11 pm](https://cloud.githubusercontent.com/assets/3979753/13039368/02adbc12-d36c-11e5-8abf-891f4b329a67.png)

##Installation

###Melpa
- Install from the melpa repo. If you haven't already, you'll need to add the following to your `.emacs`:
```Lisp
(when (< emacs-major-version 24)
  ;; For important compatibility libraries like cl-lib
  (add-to-list 'package-archives '("gnu" . "http://elpa.gnu.org/packages/")
	                          ("melpa" . "http://melpa.org/packages/")))
(package-initialize) ;; You might already have this line

```
- The package can then be installed using: **M-x package-install** [RET] dark-mint-theme

- Once installed, the theme can be loaded by running: **M-x load-theme** [RET] dark-mint

- To set as the default theme, add the following to your `.emacs` config file:

```Lisp
(load-theme 'dark-mint)
```

###Manual Installation
- Clone the repo or copy the `dark-mint-theme.el` file into either the `custom-theme-directory` or the `load-path`.

- If in placed in the `custom-theme-directory`, apply the theme with `M-x customize-themes`.

- To set as the default theme, add the following to your `.emacs` config file:

```Lisp
(load-theme 'dark-mint t)
```
