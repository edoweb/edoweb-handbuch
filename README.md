# Handbuch Webharvesting

## Installation

Clonen des git repositories:

```bash
$ git clone git@github.com:edoweb/edoweb-handbuch.git
$ cd edoweb-handbuch
```
Eigenes virtuelles Python installieren und aktivieren
```bash
$ /usr/bin/virtualenv -p /usr/bin/python3 python3
$ . python3/bin/activate
```

Sphinx installieren:
```bash
$ pip install -U Sphinx
```
Support für Markdown und Markdowntabellen nachinstallieren

```bash
$ pip install -U recommonmark
$ pip install -U sphinx-markdown-tables
```

[Read the Docs Sphinx Theme](https://github.com/readthedocs/sphinx_rtd_theme) installieren

```bash
$ pip install -U sphinx-rtd-theme
```

Für PDF-output:
```bash
$ sudo apt install texlive-latex-base latexmk texlive-latex-extra
```
