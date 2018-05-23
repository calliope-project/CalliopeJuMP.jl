
###############
CalliopeJuMP
###############

|badge_gitter| |badge_license|

-----

.. image:: https://raw.githubusercontent.com/calliope-project/calliope/master/doc/_static/logo.png

*A multi-scale energy systems (MUSES) modeling framework* | `www.callio.pe <http://www.callio.pe/>`_

-----

About
-----

The Julia Calliope backend allows the `Calliope framework <https://github.com/calliope-project/calliope>`_ to utilise the Julia package JuMP to efficiently build models and communicate with the user's chosen solver.

Calliope is a framework to develop energy system models, with a focus on flexibility, high spatial and temporal resolution, the ability to execute many runs based on the same base model, and a clear separation of framework (code) and model (data).

Quick start
-----------

CalliopeJuMP is not expected to be utilised as a stand-alone package, but instead called from the Calliope framework. By setting ``run.backend: jump``, Julia's JuMP package will be used to solve the model in the backend. Without setting this option, Calliope's `Pyomo <http://www.pyomo.org/>`_ backend will be used instead.

If the user does not have Julia or CalliopeJuMP installed on their device, they will be prompted to do so on running their model for the first time with ``run.backend: jump``.

Documentation
-------------

Documentation for Calliope is available on `Read the Docs  <https://calliope.readthedocs.io/en/stable/>`_, including the `mathematical formulation <>`_ used the solver backends.

License
-------

Copyright 2013-2018 Calliope contributors listed in AUTHORS

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

.. |badge_license| image:: https://img.shields.io/pypi/l/calliope.svg?style=flat-square
    :target: #license

.. |badge_gitter|  image:: https://img.shields.io/gitter/room/calliope-project/calliope.svg?style=flat-square
    :target: https://gitter.im/calliope-project/calliope
    :alt: Chat on Gitter
