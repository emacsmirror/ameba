## ameba.el
*An Emacs interface to [Ameba](https://github.com/crystal-ameba/ameba)*

---
[![License GPLv3](https://img.shields.io/badge/license-GPL_v3-green.svg)](http://www.gnu.org/licenses/gpl-3.0.html)
[![MELPA](https://melpa.org/packages/ameba-badge.svg)](https://melpa.org/#/ameba)
[![MELPA](https://melpa.org/packages/flycheck-ameba-badge.svg)](https://melpa.org/#/flycheck-ameba)

[Ameba](https://github.com/crystal-ameba/ameba) is a static code analysis tool
for [Crystal](https://crystal-lang.org/).

This package allows you to use this tool directly in Emacs.

Supports Ameba of version >= `0.4.2`.

### Features:

* Allows to run Ameba on the currently visited file
* Allows to run Ameba on the entire project
* Allows to prompt from a directory on which to run Ameba
* Flycheck mode

### Installation

[ameba](https://melpa.org/#/ameba) and [flycheck-ameba](https://melpa.org/#/flycheck-ameba) packages are available on Melpa.

### Usage

Run one of the predefined interactive functions.

See [Function Documentation](#function-documentation) for details.

### Function Documentation


#### `(ameba-check-current-file)`

Run check on the current file.

#### `(ameba-check-project)`

Run check on the current project.

#### `(ameba-check-directory &optional DIRECTORY)`

Run check on the DIRECTORY if present or prompt user if not.

#### `(flycheck-ameba-setup)`

Setup Flycheck Ameba.

-----
<div style="padding-top:15px;color: #d0d0d0;">
Markdown README file generated by
<a href="https://github.com/mgalgs/make-readme-markdown">make-readme-markdown.el</a>
</div>
