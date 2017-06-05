# dive-into-tango-with-django
create and finish the rango application by simulating the tutorials of "how to tango with django release1 May 13, 2017"

## fix(pil): pil module is not supported officially
**page 24**: Installing the Python Imaging Library
> $ pip install pil
**fixed**: see SO [Installing PIL with pip](https://stackoverflow.com/questions/20060096/installing-pil-with-pip)
```
Use Pillow instead, as PIL is basically dead. Pillow is a maintained fork of PIL.
https://pypi.python.org/pypi/Pillow/2.2.1
pip install Pillow
```
