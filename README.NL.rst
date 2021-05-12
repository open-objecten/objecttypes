===========
Objecttypen
===========

Een collectie van objecttypen, gemaakt en gebruikt door Nederlandse 
overheidsorganisaties, voor gebruik net de `Objecttypen API`_.
(`English version`_)

Introductie
===========

Objecttypen zijn technische definities van een object. Als elke applicatie 
dezelfde technische definitie verwacht, maakt en gebruikt, dan zou integratie
tussen systemen veel eenvoudiger zijn. Het gebruik van gemeenschappelijke 
objecttypen maken precies dit mogelijk.

Een objecttype kan van alles omschrijven: Een monument, boot, weg, boom, 
trouwambtenaar, pensioenplan, formulier, etc. Deze technische definities zijn
opgeschreven in `JSON schema`_ en het objecttype voegt meta gegevens toe om
context te bieden.

De `Objecten API`_ en de `Objecttypen API`_ zijn twee componenten die met elkaar
samen werken. De **Objecttypen API** bevat de objecttypen die objecten 
beschrijven en opgeslagen kunnen worden in de **Objects API**. Samen bieden zij
een krachtige manier om elk willekeurig object te maken en op te slaan. De
componenten zijn ontwikkeld volgens de `Common Ground`_ filosofie en kunnen
gebruikt worden in combinatie met andere API's die domein specifieke gegevens
moeten opslaan.

Zowel de objecttypen in deze repository (CC0), alsmede de Objecttypen API (EUPL)
en de Objecten API (EUPL) zijn open source en daarmee vrij en gratis te 
gebruiken.

.. _`JSON schema`: https://json-schema.org/
.. _`Objecten API`: https://github.com/maykinmedia/objects-api/
.. _`Objecttypen API`: https://github.com/maykinmedia/objecttypes-api/
.. _`Common Ground`: https://www.commonground.nl/


Hoe te gebruiken
================

Er zijn 4 mappen in deze repository:

* `community-concepts` - Bevat alle objecttypen die zijn gemaakt door de
  community. Ze worden doorgaans niet gebruikt door veel publieke organisaties, 
  kunnen wijzigen zonder kennisgeving, maar zijn hier ingediend zodat anderen er
  gebruik van kunnen maken. Als meerdere publieke organisaties een objecttype 
  gebruiken, kan deze "opgewaardeerd" worden naar een community standaard (zie 
  hieronder).
* `community-standards` - Bevat objecttypen waar een groep van publieke 
  organisaties overeenstemming over heeft bereikt. Het objecttype wordt 
  beschouwd als een *community standaard* en kan niet worden gewijzigd. Alleen 
  nieuwe versies kunnen ingediend worden als *community concept*.
* `official-concepts` - Bevat objecttypen waarvan verwacht wordt dat deze een
  officiële standaard worden maar dat nog niet zijn. Als, na een bepaalde 
  periode, er geen bezwaren zijn tegen dit objecttype, kan het "opgewaardeerd" 
  worden naar een *officiële standaard*.
* `official-standards` - Bevat objecttypen die worden aanbevolen voor alle 
  organisaties om te gebruiken. Deze objecttypen zullen normaal gesproken niet
  snel opgevolgd worden door nieuwere versies en kan hoogstwaarschijnlijk voor 
  een lange periode worden gebruikt.

Deze mappen bevatten JSON-schema's. Ze kunnen in uw eigen Objecttypen API worden
ingeladen en voorzien worden van de juiste meta gegevens.


References
==========

* `Documentatie <https://objects-and-objecttypes-api.readthedocs.io/>`_
* `Community <https://commonground.nl/groups/view/601c92bd-19c7-431a-acd5-0400d60ad666/overige-registraties-objecten-en-objecttypen-api>`_
* `Objecten API <https://github.com/maykinmedia/objects-api/>`_
* `Objecttypen API <https://github.com/maykinmedia/objecttypes-api/>`_


Licentie
========

Licensed under the `Creative Commons Zero (CC0) v1.0 Universal`_

.. _`English version`: README.rst
.. _`Creative Commons Zero (CC0) v1.0 Universal`: LICENSE
