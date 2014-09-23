protonCT
========

A library for proton CT reconstruction on the GPU. 

The code was written during the PhD of David Hansen, which resulted in the thesis "Improving Ion Computed Tomography".

The code is in an alpha stage, and while the core component (ie. reconstruction of proton CT) works well, other components are less reliable. 

In particular, the preconditioners currently implemented do NOT work well. The code for finding the convex hull of the scanned object work nicely, but the information is not currently used in a meaningful fashion.

Use of this code is strictly yor own responsibillity. I make no claims that the code is correct and cannot in any way be held responsible for the use of this code. In particular, this code is not suitable for anything resembling clinical use. You have been warned. 

Depends on the GPU components of the development branch of GADGETRON  (http://gadgetron.sourceforge.net/)



