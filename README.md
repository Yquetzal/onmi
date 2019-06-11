## Overlapping NMI in Python.

This single file library allows you to compute several versions of the NMI.

It is strongly impired by the article by McDaid et al.[1]. In fact, it is checked to provided identical results than their implementation [2] in C++ .

It allows to compute: 
* The original version of the overlapping NMI as described by Lancichinetti et al. in [3], that I call $$LFK$$
* The variation proposed in [2] to solve some normalization problems of the original version, that I call $$MGH$$
* A variant of the method in [3] introduced in [1], equation 7. (called there $$NMI_{LFK}$$, that I call $$MGH_{LFK}$$


If you use this code and want to reference it, cite it as the cdlib [4] since I wrote this code for this library.

---

[1]  McDaid, A. F., Greene, D., & Hurley, N. (2011). Normalized mutual information to evaluate overlapping community finding algorithms. arXiv preprint arXiv:1110.2515. Chicago

[2] https://github.com/aaronmcdaid/Overlapping-NMI

[3] Lancichinetti, A., Fortunato, S., & Kertesz, J. (2009). Detecting the overlapping and hierarchical community structure in complex networks. New Journal of Physics, 11(3), 033015.

[4] https://github.com/GiulioRossetti/cdlib
