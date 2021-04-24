=========
green-pie
=========


Server with video and sensor readings.

Development
===========

```workon green-pie ```
```pip3 install -e . ```

Uninstall Development Version

```sudo python3 setup.py develop -u```

Turns out pip use setup.py to do installation anyway

Instalation
===========

```python3 setup.py sdist ```
```pip3 install dist/green-pie-[version].tar.gz ```


Description
===========

Simple raspberry-pi deployed server. 
Serve video stream as well as readings from 

- temperature sensor (18b20)
- humidity sensor (dht11)§


.. _pyscaffold-notes:

Note
====

This project has been set up using PyScaffold 4.0.1. For details and usage
information on PyScaffold see https://pyscaffold.org/.
