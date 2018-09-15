# smart-mode-line-atom-one-dark-theme

## Description
An atom-one-dark theme for [smart-mode-line](https://github.com/Malabarba/smart-mode-line).

## Screenshots
### Active
![Smart Modeline Atom One Dark Theme: Active](https://raw.githubusercontent.com/daviderestivo/smart-mode-line-atom-one-dark-theme/master/screenshots/smart-mode-line-atom-one-dark-theme-active.png)

### Inactive
![Smart Modeline Atom One Dark Theme: Inactive](https://raw.githubusercontent.com/daviderestivo/smart-mode-line-atom-one-dark-theme/master/screenshots/smart-mode-line-atom-one-dark-theme-inactive.png)


## Installation
smart-mode-line is available on Melpa. Please refer to the [official doc](https://github.com/Malabarba/smart-mode-line/blob/master/README.org)
for the installation steps.

Download smart-mode-line-atom-one-dark-theme.el and copy it into your .emacs.d
theme folder:

``` bash
mkdir ~/.emacs.d/themes
```

Add the following elisp snippet into init.el:

``` elisp
;; Tell Emacs where is your personal theme directory
(add-to-list 'custom-theme-load-path (expand-file-name "themes"
                                                       user-emacs-directory))
(require 'smart-mode-line)
(setq sml/theme 'atom-one-dark)
(sml/setup)
```

If you are using use-package, please use the below elisp snippet:

``` elisp
;; Tell Emacs where is your personal theme directory
(add-to-list 'custom-theme-load-path (expand-file-name "themes"
                                                       user-emacs-directory))
(use-package smart-mode-line
  :config
  (setq sml/theme 'atom-one-dark)
  (sml/setup))
```

# Note
Currently smart-modeline-atom-one-dark theme is not available on Melpa. A
pull request has been submitted.
