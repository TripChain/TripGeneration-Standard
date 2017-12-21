Trip Generation Standard and Schema
===================================

This document represents a proposed working draft standard for Trip Generation data and a supporting schema structure for electronic application. The proposed standard was inspired by recent work done by the Institute of Transportation Engineers (ITE) since 2016 in their efforts to produce the recently released *ITE Trip Generation Manual, 10th Edition (2017)*. This standard has been developed specifically as part of the `TripChain`_ project but is made open source to further general dialogue, collaboration, and agreement within the profession to further adoption of an agreed Trip Generation Standard.

Culminating from this effort, it is the intent to produce several schema of digital formats to apply in data exchange and conversion schemes. The `TripChain`_ project applies a JavaScript Object Notation (JSON) format using priciples derived from `JSON Schema`_. The principles of the standard can be converted to schema in additional formats, such as XML, CSV, SQL, and others.

The main documentation defining the Trip Generation Standard can be found in the following sections:

* :ref:`overview-docs`
* :ref:`standard-docs`

Information and documentation for specific schema are found in the following sections:

* :ref:`schema-json-specs`
* :ref:`schema-other-specs`

This document code is open source and `available on github`_.

.. _overview-docs:
	.. toctree::
	:maxdepth: 2
	:caption: Overview Documentation

	overview/introduction
	overview/getting_started
	overview/versions
	overview/builds
	overview/features
	overview/support
	overview/faq
	overview/definitions

.. _standard-docs:
.. toctree::
	:maxdepth: 2
	:caption: Standard Documentation

	standard/introduction
	standard/general_info
	standard/land_use_variables
	standard/context_data
	standard/detailed_volumes
	standard/calculated

.. _schema-json-specs:
.. toctree::
	:maxdepth: 2
	:caption: JSON Schema Specifications

	specs/json/introduction
	specs/json/schema

.. _schema-other-specs:
.. toctree::
	:maxdepth: 2
	:caption: Other Schema Specifications

	specs/other/introduction

   rtfd

.. _TripChain: http://tripchain.org/
.. _JSON Schema: http://json-schema.org/
.. _available on github: https://github.com/TripChain/TripGeneration-Standard
