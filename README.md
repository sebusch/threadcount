# Threadcount

>In 2021-2022 I worked on a volunteer basis to assist an astrophysics research group in their data analysis.
>
>This is a code that I wrote for use in an astrophysics research group at Swinburne University. You can find the live version here: https://github.com/astrodee/threadcount
>
>I developed the software and wrote the documentation.
>
>This software carries out regression analysis on large data files. Using baysean methods combined with Monte Carlo statistical analysis, as well as visualization.
>
>As of May 2022 it is currently in use for scientific publications.

Read the documentation: [https://threadcount.readthedocs.io](https://threadcount.readthedocs.io)

This package contains tools for fitting spectral data cubes, designed for internal use by Deanne Fisher's Research Group.

It relies heavily on other packages, including [lmfit](https://lmfit.github.io/lmfit-py/index.html) and [mpdaf](https://mpdaf.readthedocs.io/en/latest/).

The idea behind this is to be a set of analysis scripts for doing common tasks, with easy configuration.

We have added some common custom models to supplement lmfit's builtin models, have extended lmfit to handle monte-carlo iterations, and have extended mpdaf to interface with lmfit to fit spectra with ease. It uses an AIC fucntion that is not the built-in lmfit AIC, due to the difference between lmfit version and the common definition of AIC.
