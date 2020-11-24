modname = {{cookiecutter.name}}
front_src = $(shell libvis-mods where --front)
back_src = $(shell libvis-mods where --back)

install:
	libvis_mods install

requirements: req_py req_js
	@echo "[libvis-mods] :I: Installed requirements"

req_py:
	pip3 install -r py_requirements.txt --user

req_js:
	cat js_requirements.txt | xargs npm i --prefix $(front_src)/$(modname)
