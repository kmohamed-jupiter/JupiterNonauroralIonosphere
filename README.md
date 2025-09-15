# JupiterNonauroralIonosphere
A python package providing field line tracing, data analysis, and plotting routines from the ISSI International Team Project 23‐592 (Jupiter's non‐auroral ionosphere).

### Documentation ###
Detailed documentation and API reference can be found at JupiterNonauroralIonosphere.readthedocs.io

### Install via pip ###
```
pip3 install JupiterNonauroralIonosphere
```
Or to upgrade to the latest version: 
```
pip3 install JupiterNonauroralIonosphere --upgrade
```

### Table of Contents

  * [Magnetic Field Line Tracing](#magnetic-field-line-tracing)
  * [Fitting observed spectra](#fitting-observed-spectra)
- [Real world (universe) examples](#real-world--universe--examples)
  * [Example 1: Grids](#example-1--grids)
  * [Example 2: Spectra](#example-2--spectra)
  * [Example 3: Temperatures](#example-3--temperatures)
- [Dummy Text](#dummy-text)
    + [Dummy Text 1](#dummy-text-1)
    + [Dummy Text 2](#dummy-text-2)
    + [Dummy Text 3](#dummy-text-3)
- [Data resources](#data-resources)


## Magnetic Field Line Tracing


The code below generate an example magnetic field line trace: 

```python
import matplotlib.pyplot as plt
import numpy as np

# Create the ZZZ object
foo = bar.ZZZ()

# Plot the model
fig, ax = plt.subplots()
ax.plot(range(1, 4), foo(range(1, 4)))
# Automagically set the labels 
ax.set_xlabel(ZZZ.xlabel())
ax.set_ylabel(ZZZ.ylabel())
plt.savefig('example_ZZZ_output.png')
plt.close() 
```
This creates the following ZZZ spectrum: 

<p align="center"> 
<img src="img/example_ZZZ_output.png">

Am example diagnostic produced in the console isWhich produces an output in the console like:

```
[ZZZ]  Object parameters:
         Number density    = 1007.2 ± 8.3 [K]
         Magnetic field dip angle = 9.81 ± 1.97E-12 [º]
         ------------------------------
         sigma-0 = 1E-01 ± 1.1E-03
         offset-0 = 1E-01 ± 1.1E-03
         background-0 = 1E-01 ± 1.1E-03
```
Which is the same temperature and density as what we produced the model with, within the error bars of the fit. The fit to the simulated H<sub>3</sub><sup>+</sup> data looks like this:

<p align="center"> 
<img src="img/example_fit.png">
</p>

# Real world (universe) applications 

Here need to summarize our shared codes.

## Example 1: Grids

Coallate text.

```python
import matplotlib.pyplot as plt
import numpy as np

```
Fill in here.

## Example 2: Spectra

Coallate text.

```python
import matplotlib.pyplot as plt
import numpy as np

```
Fill in here.


## Example 3: Temperatures

Coallate text.

```python
import matplotlib.pyplot as plt
import numpy as np

```
Fill in here.


# Dummy Text 0

Dummy Text 0

### Dummy Text 1
Dummy Text 1

### Dummy Text 2
Dummy Text 2


### Dummy Text 3

Dummy Text 

# Data resources 
`JupiterNonauroralIonosphere` uses Juno-derived magnetic field models, e<sup>-</sup> data, and H<sub>3</sub><sup>+</sup> data to produce tracing, models, and fits from the following resources:

* The H<sub>2</sub> line list and partition functioin from [Roueff et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019A%26A...630A..58R/abstract).
