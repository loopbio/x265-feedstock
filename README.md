About x265
==========

Home: https://bitbucket.org/multicoreware/x265

Package license: GPLv2

Feedstock license: BSD 3-Clause

Summary: Open Source H265/HEVC video encoder

The goal of x265 is to become the best open source H.265/HEVC encoder,
with the highest compression efficiency at the highest performance,
while also allowing commercial use via a dual GPL and commercial license.
In a nutshell, we would like to reproduce x264's successful development
model for HEVC.


Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/loopbio/x265-feedstock/master.svg?label=Linux)](https://circleci.com/gh/loopbio/x265-feedstock)
![OSX disabled](https://img.shields.io/badge/OSX-disabled-lightgrey.svg)
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-x265-green.svg)](https://anaconda.org/loopbio/x265) | [![Conda Downloads](https://img.shields.io/conda/dn/loopbio/x265.svg)](https://anaconda.org/loopbio/x265) | [![Conda Version](https://img.shields.io/conda/vn/loopbio/x265.svg)](https://anaconda.org/loopbio/x265) | [![Conda Platforms](https://img.shields.io/conda/pn/loopbio/x265.svg)](https://anaconda.org/loopbio/x265) |

Installing x265
===============

Installing `x265` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `x265` can be installed with:

```
conda install x265
```

It is possible to list all of the versions of `x265` available on your platform with:

```
conda search x265 --channel loopbio
```




Updating x265-feedstock
=======================

If you would like to improve the x265 recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/x265-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.