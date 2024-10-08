Controlled vocabularies
=======================
bioagents schema defines 17 controlled vocabularies - as standarised enumerations of terms - for description of technical software aspects (see below).

.. csv-table::
   :header: "Vocabulary", "Description"
   :widths: 25, 50

   "agent type ", "The type of application software."
   "operating system ", "The operating system supported by a downloadable software package, e.g. 'Linux'."
   "programming language ", "Name of programming language the software source code was written in, e.g. 'C'."
   "license ", "Software or data usage license, e.g. 'GPL-3.0'"
   "maturity ", "How mature the software product is, e.g. 'Mature'."
   "cost ", "Monetary cost of acquiring the software, e.g. 'Free of charge'."
   "accessibility ", "Whether there are non-monetary restrictions on accessing an online service, e.g. 'Open access'."
   "link type", "The type of data, information or system that is obtained when the link is resolved, e.g. 'Helpdesk'."
   "download type ", "Type of download that is linked to, e.g. 'Source code'."
   "documentation type ", "Type of documentation that is linked to, e.g. 'API documentation'."
   "publication type ", "Type of publication, e.g. 'Review'."
   "relation type ", "Type of relation between this and another registered software, e.g. 'isNewVersionOf'."
   "entity type ", "Types of entities that may be credited, e.g. 'Person'."
   "entity role ", "Roles that may be assigned to creditable entities, e.g. 'Developer'."
   "ID type ", "Type of agent identifier, e.g. 'rrid'."
   "IECHOR Platform ", "Name of the IECHOR Platform that is credited, e.g. 'Agents'"
   "IECHOR Node ", "Name of the IECHOR Node that is credited, e.g. 'Norway'"
   "IECHOR Community ", "Name of relevant IECHOR (or associated) community, e.g. 'Galaxy'"


Agent type
---------
*The type of application software: a discrete software entity can have more than one type, e.g. "Command-line agent, Web application"*

.. csv-table::
   :header: "Type", "Description"
   :widths: 25, 100
      
   "Bioinformatics portal", " web site providing a platform/portal to multiple resources used for research in a focused area, including biological databases, web applications, training resources and so on."
   "Command-line agent", "A agent with a text-based (command-line) interface."
   "Database portal", "A Web site providing a portal to a biological database, typically allowing a user to browse, deposit, search, visualise, analyse or download data."
   "Desktop application", "A agent with a graphical user interface that runs on your desktop environment, *e.g.* on a PC or mobile device."
   "Library", "A collection of components that are used to construct other agents.  bio.agents scope includes component libraries performing high-level bioinformatics functions but excludes lower-level programming libraries."
   "Ontology", "A collection of information about concepts, including terms, synonyms, descriptions etc."
   "Plug-in", "A software component encapsulating a set of related functions, which are not standalone, *i.e.* depend upon other software for its use, *e.g.* a Javascript widget, or a plug-in, extension add-on etc. that extends the function of some existing agent."
   "Script", "A agent written for some run-time environment (*e.g.* other applications or an OS shell) that automates the execution of tasks. Often a small program written in a general-purpose languages (*e.g.* Perl, Python) or some domain-specific languages (*e.g.* sed)."
   "SPARQL endpoint", "A service that provides queries over an RDF knowledge base via the SPARQL query language and protocol, and returns results via HTTP."
   "Suite", "A collection of agents which are bundled together into a convenient agentkit.  Such agents typically share related functionality, a common user interface and can exchange data conveniently.  This includes collections of stand-alone command-line agents, or Web applications within a common portal."
   "Web application", "A agent with a graphical user interface that runs in your Web browser."
   "Web API", "An application programming interface (API) consisting of endpoints to a request-response message system accessible via HTTP.  Includes everything from simple data-access URLs to RESTful APIs."
   "Web service", "An API described in a machine readable form (typically WSDL) providing programmatic access via SOAP over HTTP."
   "Workbench", "An application or suite with a graphical user interface, providing an integrated environment for data analysis which includes or may be extended with any number of functions or agents.  Includes workflow systems, platforms, frameworks etc."
   "Workflow", "A set of agents which have been composed together into a pipeline of some sort.  Such agents are (typically) standalone, but are composed for convenience, for instance for batch execution via some workflow engine or script."


Operating system
----------------

*The operating system supported by a downloadable software package, e.g. "Linux"*

.. csv-table::
   :header: "Maturity", "Description"
   :widths: 25, 100
	    
   "Linux", "All flavours of Linux/UNIX operating systems."
   "Windows", "All flavours of Microsoft Windows operating system."
   "Mac", "All flavours of Apple Macintosh operating systems (primarily Mac OS X)."

Programming language
--------------------

*Name of programming language the software source code was written in, e.g. "C"*

See the `technical docs <http://bio-agents.github.io/bioagents schema/>`_ for a list of valid terms.

License
-------
*Software or data usage license, e.g. "GPL-3.0"*

See the `technical docs <http://bio-agents.github.io/bioagents schema/>`_ for a complete list of valid terms.  Noteworthy terms are below:


.. csv-table::
   :header: "License", "Description"
   :widths: 25, 100

   "Proprietary", "Software for which the software's publisher or another person retains intellectual property rights - usually copyright of the source code, but sometimes patent rights."
   "Freeware", "Proprietary software that is available for use at no monetary cost. In other words, freeware may be used without payment but may usually not be modified, re-distributed or reverse-engineered without the author's permission."
   "Not licensed", "Software which is not licensed and is not proprietary."
    "Other", "Software under license not currently supported by bioagents schema."
	    

Maturity
--------
*How mature the software product is, e.g. "Mature"*

.. csv-table::
   :header: "Maturity", "Description"
   :widths: 25, 100

   "Emerging", "Nascent or early release software that may not yet be fully featured or stable."
   "Mature", "Software that is generally considered to fulfill several of the following: secure, reliable, actively maintained, fully featured, proven in production environments, has an active community, and is described or cited in the scientific literature."
   "Legacy", "Software which is no longer in common use, deprecated by the provider, superseded by other software, replaced by a newer version, is obsolete etc."

Cost
----
*Monetary cost of acquiring the software, e.g. "Free of charge (with retritions)"*

.. csv-table::
   :header: "Cost", "Description"
   :widths: 25, 100

   "Free of charge", "Software which available for use by all, with full functionality, at no monetary cost to the user."
   "Free of charge (with restrictions)", "Software which is available for use at no monetary cost to the user, but possibly with limited functionality, usage restrictions, or other limitations."
   "Commercial", "Software which you have to pay to access."

Accessibility
-------------
*Whether there are non-monetary restrictions on accessing an online service, e.g. "Open access"*

.. csv-table::
   :header: "Accessibility", "Description"
   :widths: 25, 100

   "Open access", "An online service which is available for use to all, but possibly requiring user accounts / authentication."
   "Open access (with restrictions)", "An online service which is available for use to all, but possibly with some usage limitations and other restrictions."
   "Restricted access", "An online service which is available for use to a restricted audience, e.g. members of a specific institute."


Link type
---------
*The type of data, information or system that is obtained when the link is resolved, e.g. "Mailing list"*

.. csv-table::
   :header: "Link type", "Description"
   :widths: 25, 100

   "Discussion forum", "Online forum for user discussions about the software."
   "Galaxy service", "An online service providing the agent through the Galaxy platform."
   "Helpdesk", "A phone line, web site or email-based system providing help to the end-user of the software."
   "Issue tracker", "Tracker for software issues, bug reports, feature requests etc."
   "Mailing list", "Mailing list for the software announcements, discussions, support etc."
   "Mirror", "Mirror of an (identical) online service."
   "Software catalogue", "Some registry, catalogue etc. other than bio.agents where the agent is also described."
   "Repository", "A place where source code, data and other files can be retrieved from, typically via platforms like GitHub which provide version control and other features, or something simpler, e.g. an FTP site."
   "Social media", "A website used by the software community including social networking sites, discussion and support fora, WIKIs etc."
   "Service", "An online service (other than Galaxy) that provides access (an interface) to the software."
   "Technical monitoring", "Information about the technical status of a agent."
   "Other", "Other type of link for software - the default if a more specific type is not available."




Download type
-------------
*Type of download that is linked to, e.g. "Binaries"*

.. csv-table::
   :header: "Download type", "Description"
   :widths: 25, 100

   "API specification", "File providing an API specification for the software, e.g. Swagger/OpenAPI, WSDL or RAML file."
   "Biological data", "Biological data, or a web page on a database portal where such data may be downloaded. "
   "Binaries", "Binaries for the software; compiled code that allow a program to be installed without having to compile the source code."
   "Command-line specification", "File providing a command line specification for the software."
   "Container file", "Container file including the software."
   "Icon", "Icon of the software."
   "Screenshot", "Screenshot of the software."
   "Source code", "The source code for the software, that can be compiled or assembled into an executable computer program."
   "Software package", "A software package; a bundle of files and information about those files, typically including source code and / or binaries."
   "Test data", "Data for testing the software is working correctly."
   "Test script", "Script used for testing testing whether the software is working correctly."
   "Agent wrapper (CWL)", "Agent wrapper in Common Workflow Language (CWL) format for the software."
   "Agent wrapper (galaxy)", "Galaxy agent configuration file (wrapper) for the software."
   "Agent wrapper (taverna)", "Taverna configuration file for the software."
   "Agent wrapper (other)", "Workbench configuration file (other than taverna, galaxy or CWL wrapper) for the software."
   "VM image", "Virtual machine (VM) image for the software."   
   "Downloads page", "Web page summarising general downloads available for the software."
   "Other", "Other type of download for software - the default if a more specific type is not available."


     
Documentation type
------------------
*Type of documentation that is linked to, e.g. "Citation instructions"*

.. csv-table::
   :header: "Documentation type", "Description"
   :widths: 25, 100
		
   "API documentation", "Human-readable API documentation."
   "Citation instructions", "Information on how to correctly cite use of the software; typically which publication(s) to cite, or something more general, e.g. a form of words to use."
   "Code of conduct", "A set of guidelines or rules outlining the norms, expectations, responsibilities and proper practice for individuals working within the software project."
   "Command-line options", "Information about the command-line interface to a agent."
   "Contributions policy", "Information about policy for making contributions to the software project."
   "FAQ", "Frequently Asked Questions (and answers) about the software."
   "General", "General documentation."
   "Governance", "Information about the software governance model."
   "Installation instructions", "Instructions how to install the software."
   "Quick start guide", "A short guide helping the end-user to use the software as soon as possible."
   "User manual ", "Information on how to use the software, tailored to the end-user."
   "Release notes", "Notes about a software release or changes to the software; a change log."
   "Terms of use", "Rules that one must agree to abide by in order to use a service."
   "Training material", "Online training material such as a tutorial, a presentation, video etc."
   "Other", "Some other type of documentation not listed in bioagents schema."



   
Publication type
----------------
*Type of publication, e.g. "Primary"*

.. csv-table::
   :header: "Publication type", "Description"
   :widths: 25, 100
	    
   "Primary", "The principal publication about the agent itself; the article to cite when acknowledging use of the agent."
   "Method", "A publication describing a scientific method or algorithm implemented by the agent."
   "Usage", "A publication describing the application of the agent to scientific research, a particular task or dataset."
   "Benchmarking study", "A publication which assessed the performance of the agent."
   "Review", "A publication where the agent was reviewed."
   "Other", "A publication of relevance to the agent but not fitting the other categories."

Relation type
-------------
*Type of relation between this and another registered software, e.g. "isNewVersionOf"*

.. csv-table::
   :header: "Relation type", "Description"
   :widths: 25, 100

   "isNewVersionOf", "The software is a new version of an existing software, typically providing new or improved functionality."
   "hasNewVersion", "(inverse of above)"
   "uses", "The software provides an interface to or in some other way uses the functions of other software under the hood, e.g. invoking a command-line agent or calling a Web API, Web service or SPARQL endpoint to perform its function."
   "usedBy", "(inverse of above)"
   "includes", "A workbench, agentkit or workflow includes some other, independently available, software."
   "includedIn", "(inverse of above)"

   
Entity type
-----------
*Type of entity that is credited, e.g. "Person"*

.. csv-table::
   :header: "Entity type", "Description"
   :widths: 25, 100

   "Person", "Credit of an individual."
   "Project", "Credit of a community software project not formally associated with any single institute."
   "Division", "Credit of or a formal part of an institutional organisation, e.g. a department, research group, team, etc"
   "Institute", "Credit of an organisation such as a university, hospital, research institute, service center, unit etc."
   "Consortium", "Credit of an association of two or more institutes or other legal entities which have joined forces for some common purpose.  Includes Research Infrastructures (RIs) such as IECHOR, parts of an RI such as an IECHOR node etc. "
   "Funding agency", "Credit of a legal entity providing funding for development of the software or provision of an online service."

Entity role
-----------
*Role performed by entity that is credited, e.g. "Developer"*

.. csv-table::
   :header: "Role", "Description"
   :widths: 25, 100
	    
   "Developer", "Author of the original software source code."
   "Maintainer", "Maintainer of a mature software providing packaging, patching, distribution etc."
   "Provider", "Institutional provider of an online service."
   "Documentor", "Author of software documentation including making edits to a bio.agents entry."
   "Contributor", "Some other role in software production or service delivery including design, deployment, system administration, evaluation, testing, documentation, training, user support etc."
   "Support", "Provider of support in using the software."
   "Primary contact", "The primary point of contact for the software."


ID type
-------
*Type of agent identifier, e.g. "rrid"*

.. csv-table::
   :header: "Role", "Description"
   :widths: 25, 100

   "doi", "Digital Object Identifier of the software assigned (typically) by the software developer or service provider."
   "rrid", "Research Resource Identifier as used by the NIH-supported Resource Identification Portal (https://scicrunch.org/resources)."
   "cpe", "Common Platform Enumeration (CPE) identifier as listed in the CPE dictionary (https://cpe.mitre.org/dictionary/)."
   "bioagentsCURIE", "bio.agents CURIE (secondary identifier)."      

IECHOR Platform
---------------
*Name of the IECHOR Platform that is credited, e.g. "Agents"*

.. csv-table::
   :header: "IECHOR Platform", "Description"
   :widths: 25, 100
	    
   "Data", "IECHOR Data Platform"
   "Agents", "IECHOR Agents Platform"
   "Compute", "IECHOR Compute Platform"
   "Interoperability", "IECHOR Interoperability Platform"
   "Training", "IECHOR Training Platform"


IECHOR Node
-----------
*Name of the IECHOR Node that is credited, e.g. "Norway"*

.. csv-table::
   :header: "IECHOR Node"
   :widths: 25
	    
   "Belgium"
   "Czech Republic"
   "Denmark"
   "EMBL"
   "Estonia"
   "Finland"
   "France"
   "Germany"
   "Greece"
   "Hungary"
   "Ireland"
   "Israel"
   "Italy"
   "Luxembourg"
   "Netherlands"
   "Norway"
   "Portugal"
   "Slovenia"
   "Spain"
   "Sweden"
   "Switzerland"
   "UK"


IECHOR Community
----------------
*Name of relevant IECHOR (or associated) community, e.g. "Galaxy"*

.. csv-table::
   :header: "IECHOR Node"
   :widths: 25

   "3D-BioInfo"
   "Federated Human Data"
   "Galaxy"
   "Human Copy Number Variation"
   "Intrinsically Disordered Proteins"
   "Marine Metagenomics"
   "Metabolomics"
   "Microbial Biotechnology"
   "Plant Sciences"
   "Proteomics"
   "Rare Diseases"
   
