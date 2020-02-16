## Pip publish template intended to be used by mirror-clone 
python3 -m twine upload dist/*

### To start, mirror-clone this repo
https://help.github.com/en/github/creating-cloning-and-archiving-repositories/duplicating-a-repository#mirroring-a-repository

### Before publish, build use following `cmd`
```bat
python3 setup.py sdist bdist_wheel
```

### To publish, use following `cmd`
```bat
python -m twine upload dist/*
```

### For general instruction on `PyPi` pusblish, check the python official doc link below
https://packaging.python.org/tutorials/packaging-projects/
