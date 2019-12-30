[![Version](https://img.shields.io/pypi/v/voila-tufte.svg)](https://pypi.python.org/project/voila-tufte)
[![Conda Version](https://img.shields.io/conda/vn/conda-forge/voila-tufte.svg)](https://anaconda.org/conda-forge/voila-tufte)

# voila-tufte

voila-tufte is a custom [Voilà](https://github.com/voila-dashboards/voila) 
template using [Tufte.css](https://edwardtufte.github.io/tufte-css/) in order
to render [Jupyter](https://jupyter.org) notebooks following the guidelines 
outlined in [Edward Tufte works](https://www.edwardtufte.com).

--- 

Voilà technology allows to turn Jupyter notebooks into standalone webapps.
It allows the scientific community to share its work and current research
combining the power of code (initially in Python, but today language-agnostic) 
with a narrative format offered by notebooks.

On the other hand, Edward Tufte has outlined long ago the fundamental principles 
regarding the quantitative display of information. To me, every scientist should 
have read Tufte books and gain the real sense of what "data plotting" really
means.

Now, it's time to combine both.

**However**, Voilà process Jupyter notebooks into web**apps**. As of now,
it is not possible to simply load a custom .css file into a Jupyter notebook.
Hence, one must install custom templates to be able to do so. Hence this 
repository. 

At some point, we hope to merge this work with [voila-vuetify](https://github.com/voila-dashboards/voila-vuetify).

## Installation

`voila-tufte` can be installed from PyPI

```
pip install voila-tufte
```

## Usage

To use the `tufte` template, just pass `--template=tufte` to the `voila` command line:

```
voila --template tufte tufte_example.ipynb
```

# Author

Cédric Foellmi, a.k.a. **[@onekiloparsec](https://twitter.com/onekiloparsec)** ([website](https://onekiloparsec.dev)). <br/>
(Ph.D. in astrophysics, and former *support astronomer* at the
 [European Southern Observatory](http://www.eso.org) in Chile). <br/>
 I am the author of the app iObserve (for [macOS](http://onekiloparsec.dev/iobserve) 
 (and formerly in [iOS/iPad]) and [arcsecond.io](https://www.arcsecond.io)
 and many other useful stuff for astronomers.
