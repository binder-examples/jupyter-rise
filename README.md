# Creating interactive presentations on Binder with RISE

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/binder-examples/jupyter-rise/master?filepath=index.ipynb)

In a recent release of RISE, there is support for automatically launching
the RISE plugin when a notebook is opened. This repository demonstrates how
to accomplish this for Binder.

To do this, add an `autolaunch=true` configuration
parameter to a notebook's `livereveal` section in the
metadata. When the notebook is launched, your
presentation will automatically begin. E.g.:

```
...
"livereveal": {
        "autolaunch": true
        }
...
```

See the [RISE Documentation](https://damianavila.github.io/RISE/)
for more information.
