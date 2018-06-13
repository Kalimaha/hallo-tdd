# Hallo, World! - TDD Version

Very basic project used to practice TDD.

## Run with Docker

First, build the Docker container:

```
docker-compose build tdd
```

Them run tests:

```
docker-compose run tdd python setup.py test
```

You should see something like this:

```
running pytest
running egg_info
writing hallo_tdd.egg-info/PKG-INFO
writing dependency_links to hallo_tdd.egg-info/dependency_links.txt
writing top-level names to hallo_tdd.egg-info/top_level.txt
reading manifest file 'hallo_tdd.egg-info/SOURCES.txt'
writing manifest file 'hallo_tdd.egg-info/SOURCES.txt'
running build_ext
Test session starts (platform: linux, Python 3.6.1, pytest 3.6.1, pytest-sugar 0.9.1)
rootdir: /app, inifile: setup.cfg
plugins: sugar-0.9.1, pep8-1.0.6

 tests/__init__.py ✓                                                                              33% ███▍
 tests/calculator_test.py ✓✓                                                                     100% ██████████

Results (0.07s):
       3 passed
```
