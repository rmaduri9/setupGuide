# Setup Guides
*Mac OSX El Capitan 10.11.6*, MacBook Pro (15 inch, Mid 2009), 3.06 GHz Intel Core 2 Duo

Django in Virtualenv

The following two packages to be installed on the local machine as sudo.
* sudo easy_install pip
* sudo pip install virtualenv

In Mac OSX Python can be found (which python)
/Library/Frameworks/Python.framework/Versions/

* virtualenv --python=python3 py3

activate the created virtualenv py3

* cd py3/bin
* . ./activate

To get a list of Python modules installed.
* pip freeze

To Install django specific version
* pip install django==1.8.13

To update django to latest version
* pip install django —upgrade


