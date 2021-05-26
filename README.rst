===========
Objecttypes
===========

A collection of objecttypes, created and used by Dutch government organizations,
for use with the `Objecttypes API`_.
(`Nederlandse versie`_)

Introduction
============

Objecttypes are technical definitions of an object. If every application can
expect, create and use the same technical definition for an object, integration 
between systems would be much easier. The use of objecttypes that everyone 
agreed upon, allow for exactly this.

An objecttype can describe anything: A monument, boat, road, tree, marriage 
official, pension plan, form, etc. These technical definitions are described as 
a `JSON schema`_ and the objecttype adds some meta information to offer context
for this JSON schema.

The `Objects API`_ and the `Objecttypes API`_ are two components that complement 
eachother. The **Objecttypes API** holds the objecttypes for objects that can 
be stored in the **Objects API**. Together they provide a powerfull way to 
create and store any kind of object. They are designed in line with the 
`Common Ground`_ philosophy and they can be used by other API's that need to 
store domain specific data.

The objecttypes in this repository (CC0), and also the Objecttypes API (EUPL)
and the Objects API (EUPL) are open source and therefore free to use.

.. _`JSON schema`: https://json-schema.org/
.. _`Common Ground`: https://www.commonground.nl/


Participants in the community standards
---------------------------------------

The `Objects API`_ and the `Objecttypes API`_ are in the process of 
standardization within `VNG`_. Meanwhile, several public organizations have 
indicated they will (plan to) use and support these API's. They intent to use 
objecttypes and will actively contribute by providing new and/or improved 
objecttypes and share them here.

A, most likely incomplete, list of participants is shown below:

* `Dimpact <https://www.dimpact.nl/>`_ (cooperation of 40+ municipalities)
* `GBI <https://gbi-gemeenten.nl/>`_ (part of VNG)
* Municipality of Utrecht
* Municipality of Delft
* Municipality of Amsterdam
* Municipality of Rotterdam (also member of Dimpact)
* Municipality of Haarlem

.. _`Objects API`: https://github.com/maykinmedia/objects-api/
.. _`Objecttypes API`: https://github.com/maykinmedia/objecttypes-api/
.. _`VNG`: https://www.vngrealisatie.nl/


How to use
==========

There are 4 folders in this repository:

* **community-concepts** - Contains all objecttypes that are created by the 
  community. They are typically not used by many public organizations, can 
  change without notice but submitted here to benefit and provide inspiration 
  to others. If multiple public organizations use an objecttype, it can be 
  "upgraded" to a community standard (see below).
* **community-standards** - Contains objecttypes that a group of public 
  organizations agreed upon. The objecttype is considered to be a 
  *community standard* and cannot be changed. Only newer versions can be 
  submitted as *community concept*.
* **official-concepts** - Contains objecttypes that are considered to become an 
  official standard but are not yet there. If, after a certain period, there
  are no objections to this objecttype, it can be "upgraded" to an 
  *official standard*.
* **official-standards** - Contains objecttypes that are recommended for all 
  organizations to use. These objecttypes will typically not see newer versions
  anytime soon and can most likely be used for a long period of time.

These folders contain JSON schemas. They can be loaded into your own Objecttypes
API with appropriate meta data.


References
==========

* `Documentation <https://objects-and-objecttypes-api.readthedocs.io/>`_
* `Community <https://commonground.nl/groups/view/601c92bd-19c7-431a-acd5-0400d60ad666/overige-registraties-objecten-en-objecttypen-api>`_
* `Objects API <https://github.com/maykinmedia/objects-api/>`_
* `Objecttypes API <https://github.com/maykinmedia/objecttypes-api/>`_


Licence
=======

Licensed under the `Creative Commons Zero (CC0) v1.0 Universal`_

.. _`Nederlandse versie`: README.NL.rst
.. _`Creative Commons Zero (CC0) v1.0 Universal`: LICENSE
