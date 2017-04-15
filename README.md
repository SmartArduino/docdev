# shenzhendoit.com

[![Build Status](https://readthedocs.org/projects/glpi-developer-documentation/badge/?version=latest)](http://glpi-developer-documentation.readthedocs.io/en/latest/?badge=latest)

Current documentation is built on top of [Sphinx documentation generator](http://sphinx-doc.org/). It is released under the terms of the <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons BY-NC-ND 4.0 International License</a>.

## Run it!

You'll just have to install [Python Sphinx](http://sphinx-doc.org/), it is generally available in distributions repositories for Linux.

If your distribution does not provide it, you could use a `virtualenv`:
```
$ virtualenv /path/to/virtualenv/files
$ /path/to/virtualenv/bin/activate
$ pip install sphinx
```

Once all has been successfully installed, just run the following to build the documentation:
```
$ make html
```

Results will be avaiable in the `build/html` directory :)

Note that it actually uses the default theme, which differs locally and on readthedocs system.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png" /></a>
