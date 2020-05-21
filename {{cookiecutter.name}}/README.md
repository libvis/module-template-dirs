
<div align="center">
    <img width="312px" alt="libvis logo" src="http://libvis.dev/libvis-sm.png"/>
</div>

This is a {{cookiecutter.name}} [libvis](http://libvis.dev) module.

# Installation

```
libvis-mods download gh:libvis/{{cookiecutter.name}}
cd {{cookiecutter.name}}
libvis-mods install
```

# Usage 

```python
from libvis import Vis
from libvis.modules import {{cookiecutter.name}}

vis = Vis()
vis.start()

vis.vars.test = {{cookiecutter.name}}()
```

The state of `vis.vars.test` will be visualised live at `localhost:7000/`. 
