Trip Generation Standard and Schema
===================================

This document represents a proposed working draft standard for Trip Generation data and a supporting schema structure for electronic application. The proposed standard was inspired by recent work done by the Institute of Transportation Engineers (ITE) since 2016 in their efforts to produce the recently released *ITE Trip Generation Manual, 10th Edition (2017)*. This standard has been developed specifically as part of the *`TripChain_`* project but is made open source to further general dialogue, collaboration, and agreement within the profession to further adoption of an agreed Trip Generation Standard.

Culminating from this effort, it is the intent to produce several schema of digital formats to apply in data exchange and conversion schemes. The *`TripChain_`* project applies a JavaScript Object Notation (JSON) format using priciples derived from `JSON Schema`_. The principles of the standard can be converted to scheme in additional formats, such as XML, CSV, SQL, and others.




The main documentation for the site is organized into the following sections:

* :ref:`user-docs`
* :ref:`feature-docs`
* :ref:`about-docs`

Information about development is available under the following sections:

* :ref:`tech-specs`
* :ref:`dev-docs`
* :ref:`design-docs`
* :ref:`ops-docs`

The code is open source, and `available on github`.

.. _user-docs:
.. toctree::
	:maxdepth: 2
	:caption: User Documentation

	user/getting_started
	user/versions
	user/builds
	user/features
	user/support
	user/faq

.. _tech-specs:
.. toctree::
   :maxdepth: 2
   :caption: Technical Specifications

   techspecs/proj_goals
   techspecs/arch_infra
   techspecs/user_interface
   techspecs/bkgd_tasks
   techspecs/db_model
   techspecs/sys_interface
   techspecs/non_funct
   techspecs/dictionary

.. _feature-docs:
.. toctree::
   :maxdepth: 2
   :caption: Feature Documentation

   webhooks
   badges
   alternate_domains
   localization
   vcs
   conda
   canonical
   single_version
   privacy
   user-defined-redirects
   automatic-redirects
   features/*

.. _dev-docs:
.. toctree::
   :maxdepth: 2
   :caption: Developer Documentation

   team
   install
   changelog
   contribute
   tests
   architecture
   development/standards
   development/buildenvironments
   symlinks
   settings
   i18n
   issue-labels

.. _business-docs:
.. toctree::
   :maxdepth: 2
   :caption: Business Documentation

   business/index

.. _custom-docs:
.. toctree::
   :maxdepth: 2
   :caption: Custom Install Documentation

   custom_installs/index

.. _design-docs:
.. toctree::
   :maxdepth: 2
   :caption: Designer Documentation

   design
   theme

.. _about-docs:
.. toctree::
   :maxdepth: 2
   :caption: About Documentation

   open-source-philosophy
   sponsors
   talks

.. _ops-docs:
.. toctree::
   :maxdepth: 2
   :caption: Operations Documentation

   rtfd

.. _TripChain: http://tripchain.org/
.. _JSON Schema: http://json-schema.org/
