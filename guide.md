# [Sphinx](http://sphinx-doc.org/latest/index.html)

_tutorial for documentation with Sphinx_
## Sphinx tutorial by Brandon Rhodes #

* [on Youtube 2013](https://www.youtube.com/watch?v=QNHM7q2hLh8)
* [GitHub files](https://github.com/brandon-rhodes/sphinx-tutorial)

=====================================================
##Getting [Python](https://www.python.org/)

wget the recent Python version

`wget "https://www.python.org/ftp/python/3.4.2/Python-3.4.2.tar.xz"`

or

`wget "https://www.python.org/ftp/python/3.5.0/Python-3.5.0a2.tar.xz"`

then

`tar xf Python-3.4.2.tar.xz`

`cd Python && ./configure`

`make && make test && sudo make install`

`python setup.py install`


##command lines to get Sphinx

### Install Sphinx #

`apt-get install python-sphinx && sudo easy_install -U Sphinx`

### starting sphinx #

`sphinx-quickstart`

### running the build #

`make html`

`make latexpdf`
