# Warning

This library is still **Work in Progress**. No feature requests in these early development stages please. Expect major interface changes coming. 

# Description

[libfacerec](http://www.github.com/bytefish/libfacerec) is a library for face recognition in OpenCV. There are no additional dependencies to build the library. The Eigenfaces, Fisherfaces method and Local Binary Patterns Histograms (LBPH) are implemented and most parts of the library are covered by unit tests. 

# Tutorial

The documentation of the library comes with a high-level description of the API and carefully designed tutorials. It is available in the `doc/build` folder coming with this project. If you want to compile the documentation yourself, then switch to the folder `doc` and run `make <target>`. For the html version you would `make html` and for the PDF version `make latexpdf`. You'll need [Sphinx](http://sphinx.pocoo.org) for this. 

# Literature

* Eigenfaces (Turk, M., and Pentland, A. "Eigenfaces for recognition.". Journal of Cognitive Neuroscience 3 (1991), 71–86.)
* Fisherfaces (Belhumeur, P. N., Hespanha, J., and Kriegman, D. "Eigenfaces vs. Fisherfaces: Recognition using class specific linear projection.". IEEE Transactions on Pattern Analysis and Machine Intelligence 19, 7 (1997), 711–720.)
* Local Binary Patterns Histograms (Ahonen, T., Hadid, A., and Pietikainen, M. "Face Recognition with Local Binary Patterns.". Computer Vision - ECCV 2004 (2004), 469–481.)

