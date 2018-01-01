![Viper](http://viper.li/viper.png)

Viper is a binary analysis and management framework. Its fundamental objective is to provide a solution to easily organize your collection of malware and exploit samples as well as your collection of scripts you created or found over the time to facilitate your daily research.

For more information visit [viper.li](http://viper.li/)

<hr />

[![Build Status](https://api.travis-ci.org/viper-framework/viper.png?branch=master)](https://travis-ci.org/viper-framework/viper)
[![codecov](https://codecov.io/gh/viper-framework/viper/branch/master/graph/badge.svg)](https://codecov.io/gh/viper-framework/viper)

**Wanna contribute?** Viper is an open, BSD-licensed, collaborative development effort that heavily relies on contributions from the whole community. We welcome tickets, pull requests, feature suggestions.

When develping new modules or patches, please try to comply to the general code style that we try to maintain across the project. When introducing new features or fixing significant bugs, please also include some concise information and possibly also introduce comprehensive documentation in our guide.

<!--<hr />

Viper is now using [BitHub](https://whispersystems.org/blog/bithub) system to reward developers and contributors with Bitcoins. You can read more details about it [here](http://viper.li/blog/2014-07-15-viper-bitcoin.html) and you can start donating Bitcoins to this wallet **15xrTWmduftdHezxiCZyC1yFLo5RJXaAZS**. This is the current reward per commit:

[![BitHub](https://viperbithub.herokuapp.com/v1/status/payment/commit)](http://viper.li/blog/2014-07-15-viper-bitcoin.html)-->
This project is based on frennkie's viper [repo](https://github.com/frennkie/viper/tree/django_web_wip) 
<hr />

### Viper API & Web Interface

Django (with Django Rest Framework)


#### Clone and check out and install requirements

```
git clone https://github.com/frennkie/viper
cd viper
git checkout django
git submodule init
git submodule update
pip install -rrequirements.txt
```

#### Setup and start Django

```
./manage.py runserver
```

#### Site

http://127.0.0.1:8080/

#### Mac Issues

##### Main Page (Safari)

Upload doesn't do anything

##### Modules

```
Missing dependency, install virustotal-api (`pip install virustotal-api`)
Missing dependency, install virustotal-api (`pip install virustotal-api`)
```
