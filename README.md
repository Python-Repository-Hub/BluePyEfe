<!-- <img src="docs/source/logo/BluePyOptBanner.png"/> -->

-----------------

# BluePyEfe: Blue Brain Python E-feature extraction

<!--
<table>
<tr>
  <td>Latest Release</td>
  <td>
    <a href="https://pypi.org/project/bluepyopt/">
    <img src="https://img.shields.io/pypi/v/bluepyopt.svg" alt="latest release" />
    </a>
  </td>
</tr>
<tr>
  <td>Documentation</td>
  <td>
    <a href="https://bluepyopt.readthedocs.io/">
    <img src="https://readthedocs.org/projects/bluepyopt/badge/?version=latest" alt="latest documentation" />
    </a>
  </td>
</tr>
<tr>
  <td>License</td>
  <td>
    <a href="https://github.com/BlueBrain/bluepyopt/blob/master/LICENSE.txt">
    <img src="https://img.shields.io/pypi/l/bluepyopt.svg" alt="license" />
    </a>
</td>
</tr>
<tr>
  <td>Build Status</td>
  <td>
    <a href="https://travis-ci.org/BlueBrain/BluePyOpt">
    <img src="https://travis-ci.org/BlueBrain/BluePyOpt.svg?branch=master" alt="travis build status" />
    </a>
  </td>
</tr>
<tr>
  <td>Coverage</td>
  <td>
    <a href="https://codecov.io/gh/BlueBrain/bluepyopt">
    <img src="https://codecov.io/github/BlueBrain/BluePyOpt/coverage.svg?branch=master" alt="coverage" />
    </a>
  </td>
</tr>
<tr>
	<td>Gitter</td>
	<td>
		<a href="https://gitter.im/bluebrain/bluepyopt">
		<img src="https://badges.gitter.im/Join%20Chat.svg"
	</a>
	</td>
</tr>
</table>
-->

Introduction
============

BluePyEfe aims at easing the process of reading experimental recordings and extracting 
batches of efeatures from these recordings. To do so, it combines trace reading
functions and features extraction functions from the [eFel library](https://github.com/BlueBrain/eFEL).

BluePyEfe outputs protocols and features files in the format used
by [BluePyOpt](https://github.com/BlueBrain/BluePyOpt) for neuron model
 building.

Support
=======
We are providing support using a chat channel on [Gitter](https://gitter.im/BlueBrain/BluePyEfe).

News
====

Requirements
============

* [Python 2.7+](https://www.python.org/download/releases/2.7/) or [Python 3.6+](https://www.python.org/downloads/release/python-360/)
* [Pip](https://pip.pypa.io) (installed by default in newer versions of Python)
* [eFEL eFeature Extraction Library](https://github.com/BlueBrain/eFEL) (automatically installed by pip)
* [Numpy](http://www.numpy.org) (automatically installed by pip)
* [Pandas](http://pandas.pydata.org/) (automatically installed by pip)
* [Scipy](https://www.scipy.org/) (automatically installed by pip)
* [Neo](https://neo.readthedocs.io/en/stable/) (automatically installed by pip)
* The instruction below are written assuming you have access to a command shell
on Linux / UNIX / MacOSX / Cygwin

Installation
============

To install BluePyEfe run in the cloned directory:

```bash
pip install -e .
```

Quick Start
===========


API documentation
==================
The API documentation can be found on [ReadTheDocs](http://bluepyefe.readthedocs.io/en/latest/).

Funding
=======
This work has been partially funded by the European Union Seventh Framework Program (FP7/2007­2013) under grant agreement no. 604102 (HBP), the European Union’s Horizon 2020 Framework Programme for Research and Innovation under the Specific Grant Agreement No. 720270, 785907 (Human Brain Project SGA1/SGA2).