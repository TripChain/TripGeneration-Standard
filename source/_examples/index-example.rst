TripChain-Core Documentation
============================

This documentation represents the core files of the TripChain framework. The core consists of the components that make up a node within the TripCahin network, including blockchain transaction records and the disaggregated trip generation database.

At this time, the TripChain network and database should be considered a TestNet as it is currently undergoing active development and is not yet finalized. Please use associated data and services with caution as they are not yet production ready. This project will remain proof-of-concept until further notice.

The main documentation for the site is organized into a few sections:

* :ref:`user-docs`
* :ref:`feature-docs`
* :ref:`about-docs`

Information about development is available under the following sections:

* :ref:`tech-specs`
* :ref:`dev-docs`
* :ref:`design-docs`
* :ref:`ops-docs`

The code is open source, and `available on github`_.

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

.. _available on github: https://github.com/TripChain/tripchain-core



2.Define the system architecture/infrastructure
3.Define the user dialogs and the control flow
4.Define the background tasks
5.Define the database model
6.Define the interfaces to other systems
7.Define the non functional requirements (response times, security, ...)
8.Define a dictionary for all relevant concepts/entities (dangerous, you may omit this one)
Don't be too specific about system internals.


OLD LINKS FOR REFERENCE

The main documentation for the site is organized into a couple sections:

* :ref:`user-docs`
* :ref:`feature-docs`
* :ref:`about-docs`

Information about development is also available:

* :ref:`dev-docs`
* :ref:`design-docs`
* :ref:`ops-docs`



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