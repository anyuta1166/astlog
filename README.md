Install
-------

```bash
$ yum install virtualenv
$ virtualenv env/astlog
$ source env/astlog/bin/activate
$ python setup.py develop
```

If setup.py fails because of SSL error:

```bash
$ pip install pip==1.2.1      # downgrade to older version of pip which works over http
$ pip install urwid
$ python setup.py develop
```

Install as global script
------------------------

```bash
$ ln -s /opt/slsolucije/astlog/env/astlog/bin/astlog /usr/local/bin/astlog
```
