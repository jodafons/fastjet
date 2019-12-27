# FastJet

The FastJet package, written by Matteo Cacciari and Gavin Salam and
Gregory Soyez, provides a fast implementation of several
longitudinally invariant sequential recombination jet algorithms, in
particular the longitudinally invariant kt jet algorithm, the
inclusive longitudinally invariant version of the Cambridge/Aachen
jet-algorithm, and the inclusive anti-kt algorithm.

The implementation is based on the geometrical methods described in
M. Cacciari and G.P. Salam, Phys. Lett. B 641 (2006) 57
[hep-ph/0512210]. The full FastJet manual is available as
doc/fastjet-doc.tex and also as arXiv:1111.6097.

Means are also provided for accessing external jet-algorithm software
via a common (plugin) interface and the package notably includes
SISCone, an infrared safe seedless stable-cone type algorithm introduced
in G.P. Salam and G. Soyez, JHEP 0705 (2007) 086 [arXiv:0704.0292].

Various tools are also provided related to jet areas and
subtraction. They can be used with any infrared safe jet algorithm,
both native and plugin. The ideas behind them are described in
M. Cacciari, G.P. Salam, Phys.Lett.B 659 (2008) 119 [arXiv:0707.1378], and
M. Cacciari, G.P. Salam and G. Soyez, JHEP 0804 (2008) 005 [arXiv:0802.1188]

Tools are also provided to facilitate jet substructure analyses.

# Installation


```bash
mkdir .bin && .bin
git clone https://github.com/jodafons/fastjet.git && cd fastjet
./configure
make -j4
```





