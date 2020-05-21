<div align="center">
    <img width="212px" alt="libvis logo" src="http://libvis.dev/libvis-sm.png"/>
</div>

![](https://github.com/libvis/module-template-dirs/workflows/.github/workflows/test_install.yml/badge.svg)

This is a template for a libvis module

# Quickstart

```
pip install cookiecutter
cookiecutter gh:libvis/module-template-dirs
```

Answer the questions, and the tool will generate a new directory with name of the package.

To start development, run

```
libvis-mods develop
```
It will start a server and open the app in browser. 
The server will watch both front and back files and recompile/update object when files are written. 

To install the module, use `libvis-mods` in the module directory.

```
libvis-mods install
```


