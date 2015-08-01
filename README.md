# Octopress.el #

[![MELPA](http://melpa.org/packages/octopress-badge.svg)](http://melpa.org/#/octopress)

Octopress.el is a lightweight wrapper script to help you interact with Octopress
blog site and the related Jekyll programs. This package is designed to be
unobtrusive and to defer to Octopress and Jekyll as often as possible.

This package was built with the assumption of Octopress 3.0 and will probably
not work with previous (non-gem) versions of Octopress. Specifically, it expects
to be able to use commands like `octopress new post` rather than the old-style
`rake new_post[]`.

## Installation ##

Place octopress.el in your load path, or install from MELPA.

## Configuration ##

There are some configuration options. Run `M-x configure-group octopress-mode` to
see them.

## Usage ##

A more complete manual is available in Info format; see `C-h i` and follow the
Octopress link.
