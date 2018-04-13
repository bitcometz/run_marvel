run_marvel - a highly automated pipeline for MARVEL
================================================================================

`MARVEL <https://github.com/schloi/MARVEL>`__ consists of a set of tools that facilitate the overlapping, patching, correction and assembly of noisy long reads, for example PacBio or ONT. However, this program contains many steps, so it will take a lot of time to write the scripts each time you run a genome project.


**run_marvel**, is a wrapper script written in Python, which controls all the execution of scripts of MARVEL. With it, you just have to to prepare a config file and perform a simple command operation. Besides, it help you organize the relevant file directories to make all the temporary files and results look neat and orderly so that you can easily get what you want.

**Notably**, most of our description are from the MARVEL paper (see reference). 


**(对于中文读者)** You can also download the `Chinese document for MARVEL <https://github.com/bitcometz/run_marvel/raw/master/marvel_chinese.pdf>`__


