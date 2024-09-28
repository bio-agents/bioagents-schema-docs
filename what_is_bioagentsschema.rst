What is bioagents schema?
=======================

**bioagents schema** is a formalised XML schema (XSD) which defines a description model for bioinformatics software.  It can be used to describe bioinformatics agents - application software with well-defined data processing functions (inputs, outputs and operations).   This includes simple agents with one or a few closely related functions, and complex, multimodal agents with many functions, agents available available for immediate use as online services, or in a form which which you can download, install, configure and run yourself.  

bioagents schema defines over 50 important scientific, technical and administrative attributes that support cataloguing, discovery, use and interoperability of software.  It concentrates upon the salient common features, with a minimal core of 3 attributes only (name, short description and homepage), to provide maximum flexibility for applications.  To enable concise information, standard identifiers are used where possible, including `EDAM ontology <http://github.com/edamontology/edamontology>`_ concept IDs for specialised scientific aspects.  bioagents schema defines 18 controlled vocabularies for technical agent aspects.  Verbose information is referred to by URL.

bioagents schema together with the `EDAM ontology <https://github.com/edamontology/edamontology>`_ provide the foundation for an `information standard <https://github.com/bio-agents/Agent-Information-Standard>`_ for the description of agents.  This standard is being adopted by bio.agents and defines the attributes that must be defined within a 5-tier scale of entry completeness and quality.

bioagents schema is used by the IECHOR Agents & Data Services Registry (`bio.agents <https://bio.agents>`_).


How to contribute to bioagents schema
-----------------------------------

Contributions to bioagents schema are very welcome. Github being our primary communication channel, please do not hesitate to open issues, or comment on them. Pull requests are also welcome! 
The list of repositories hosting bioagents schema and its documentation are listed below. All materials are available under the :doc:`CC-BY-SA 4.0 license<license>`.

Documentation
-------------
These docs describe the latest stable version (currently 3.0.0) and are maintained in `GitHub <https://github.com/bio-agents/bioagents-schemadocs/>`_.  Additional documentation is available:

- `Technical docs <http://bio-agents.github.io/bioagents schema/>`_ maintained in `GitHub <https://github.com/bio-agents/bioagents schema/tree/master/stable/>`_ where you'll find example data files
- Usage guidelines including the bio.agents `Curators Guide <http://bioagents.readthedocs.io/en/latest/curators_guide.html#>`_ and `API Usage Guide <http://bioagents.readthedocs.io/en/latest/api_usage_guide_dev.html>`_

.. note::
   Version 3.0.0 is currently supported in `bio.agents <https://bio.agents>`_.


Download
--------
**Latest stable version** (3.0.0)

- https://github.com/bio-agents/bioagents schema/blob/master/stable/bioagents.xsd

**Current development version**

- https://github.com/bio-agents/bioagents schema/blob/master/bioagents_dev.xsd
  
**Versioned releases**

- https://github.com/bio-agents/bioagents schema/tree/master/versions


Status
------
bioagents schema is a mature schema having undergone a lot of community-driven revision (*e.g.* see `bio.agents events <http://bioagents.readthedocs.io/en/latest/events.html>`_).  Development is use-case driven, primarily by `bio.agents <https://bio.agents>`_.  Future versions will not depart fundamentally from the current elements or structure.  The development of bioagents schema can be followed at `GitHub <https://github.com/bio-agents/bioagents-schema/>`_.  From version 2.0.0, version numbers follow the `MAJOR.MINOR.PATCH` pattern:

* `MAJOR` version for incompatible API changes
* `MINOR` version for addition of functionality in a backwards-compatible manner
* `PATCH` version for backwards-compatible bug fixes

Please contribute via `GitHub <https://github.com/bio-agents/bioagents schema>`_.  See also the bio.agents `Contributors Guide <http://bioagents.readthedocs.org/en/latest/contributors_guide.html>`_. 

Motivation
----------
Bioinformaticians routinely use a large and diverse set of agents and data, and demand powerful and convenient means to organise, find, understand, compare, select, use and connect the available resources. These tasks rely on consistent, machine-understandable resource descriptions. The need - filled by bioagents schema - is for an information model that puts the description of a broad range of resources  on a consistent syntactic basis. 

Citing bioagents schema
---------------------
If you use bioagents schema, please cite:

Ison J. et al. (2021) bioagents schema: a formalized schema for bioinformatics software description. *GigaScience*, **10** (1)

The article is `freely available <https://academic.oup.com/gigascience/article/10/1/giaa157/6121637>`_.

doi: `10.1093/gigascience/giaa157 <https://doi.org/10.1093/gigascience/giaa157>`_ 




