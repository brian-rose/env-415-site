---
layout: post
title: "Installing the climlab software"
categories:
---
Starting now, and continuing until the end of the semester, we will be using a custom Python package called `climlab` (in addition to Python, numpy, matplotlib, etc.) `climlab` has code for lots of bits and piece of climate models that we will use in our exercises.

To install `climlab`, I recommend opening a command prompt on your laptop, and do this:

```
conda install netcdf4
```

(this will install a package for reading/writing data files that we will need)

and then do this:

```
pip install climlab
```

After this, you should open a Python session and type
```
import climlab
```
and ensure that there are no error messages.
