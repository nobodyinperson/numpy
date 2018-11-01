# RPM Package for SailfishOS

This branch can be used to build NumPy on a SailfishOS device.

The following packages are needed for the build process:

```
python3-cython
python3-devel
```

You might only get them on [OpenRepos.net](https://openrepos.net)

To build the RPM package, run

```bash
python3 setup.py bdist_rpm
```

It takes pretty long on a Jolla Phone, but should eventually succeed and there
will be an RPM package under `dist/`.

# <img alt="NumPy" src="https://cdn.rawgit.com/numpy/numpy/master/branding/icons/numpylogo.svg" height="60">

[![Travis](https://img.shields.io/travis/numpy/numpy/master.svg?label=Travis%20CI)](https://travis-ci.org/numpy/numpy)
[![AppVeyor](https://img.shields.io/appveyor/ci/charris/numpy/master.svg?label=AppVeyor)](https://ci.appveyor.com/project/charris/numpy)

NumPy is the fundamental package needed for scientific computing with Python.

- **Website (including documentation):** http://www.numpy.org
- **Mailing list:** https://mail.python.org/mailman/listinfo/numpy-discussion
- **Source:** https://github.com/numpy/numpy
- **Bug reports:** https://github.com/numpy/numpy/issues

It provides:

- a powerful N-dimensional array object
- sophisticated (broadcasting) functions
- tools for integrating C/C++ and Fortran code
- useful linear algebra, Fourier transform, and random number capabilities

If ``nose`` is installed, tests can be run after installation with:

    python -c 'import numpy; numpy.test()'

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)
