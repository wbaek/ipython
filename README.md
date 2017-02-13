# ipython

## ipython setup
* install
```
pip install -r requirements.txt
```

* setup & configuration
```
ipython profile create nbserver
```
[ipython notebook server configuration guide](http://ipython.org/ipython-doc/1/interactive/public_server.html#notebook-public-server)

* run
```
jupyter notebook --notebook-dir=./notebooks/ --config=jupyter_notebook_config.py --log-level=CRITICAL --no-browser
```

* ipython tutorial
http://cs231n.github.io/ipython-tutorial/

