
<div align="center">
    <img width="312px" alt="libvis logo" src="http://libvis.dev/libvis-sm.png"/>
</div>

This is a {{cookiecutter.name}} [libvis](http://libvis.dev) module


# Installation

```
libvis-mods download gh:libvis/{{cookiecutter.name}}
cd data_access_wrapper
libvis-mods install
```


# Usage

```python
from libvis.modules import {{cookiecutter.name}}
from libvis import Vis

vis = Vis()

vis.vars.test = data_access_wrapper.test_object()

```


# Documentation

[docs.libvis.dev](http://docs.libvis.dev)
