OpenWPM
=======

See the [wiki](https://github.com/citp/OpenWPM-dev/wiki) for a more in-depth tutorial.

Install Dependencies
--------------------

A mostly updated list of dependencies, this should enable you to run things on a clean
install of ubuntu.

sudo apt-get update

sudo apt-get install htop git firefox python-dev python-pip libxml2-dev libxslt-dev libffi-dev libssl-dev build-essential xvfb

sudo pip install pyvirtualdisplay beautifulsoup4 selenium netlib pyasn1 PyOPenSSL mitmproxy python-dateutil tld pyamf

git clone https://github.com/citp/OpenWPM-dev/
git config --global user.name your\_user\_name

If you need flash on Ubuntu 14.04 64-bit Amazon EC2 instance, run the following:

sudo sh -c 'echo "deb http://archive.canonical.com/ubuntu/ trusty partner" >> /etc/apt/sources.list.d/canonical\_partner.list'

sudo apt-get update

sudo apt-get install adobe-flashplugin
