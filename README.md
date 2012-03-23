Description
-------
API Blender allows you to easily interact with multiple Web services.

API Blender has been developed as part of the
ARCOMEM project, <http://arcomem.eu>.

Requirements
------------
* python 2.7.1+
* Simplegeo oauth2 python implementation:
    1. cd /tmp/
    2. git clone https://github.com/simplegeo/python-oauth2
    3. cd python-oauth2
    4. sudo python setup.py install

Run
---
* Configure config/general.json
* If you want to use authentication, config config/apis/auth

Then run:
```
./example.py
```

License
-------
Copyright (C) 2011  Georges GOURITEN 

MIT License
