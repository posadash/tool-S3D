# tool-S3D

1. General information

Overview

S3D is a UML/MARTE model-driven design framework. S3D supports a “single-source approach” to Electronic System-Level (ESL) design activities, which improve design productivity. The framework automates several ESL design activities, e.g., the production of functional models, of performance models, design space exploration, etc. The input of the design methodology is a model relying on existing standards, namely UML and additional OMG standard UML profiles, i.e. MARTE. The UML/MARTE model is used as a single, centralized repository of all the information about the system relevant for the design. This leverages consistency and modelling efficiency. The framework automates several ESL design activities, e.g., the production of functional models, of performance models, design space exploration, etc.
The two main tools to be improved and assessed in MegaMart are, VIPPE, the simulation and performance analysis tool and eSSYN, the SW synthesis tool.

Website
  umlmarte.teisa.unican.es

Download
  umlmarte.teisa.unican.es
 
Installation
S3D is a framework, requiring the installation of different modules depending on the activities to be performed. The main (core) module is based on eclipse, and it can be directly downloaded from the S3D download web page, or installed as an Eclipse component both in precompiled or source form, following the next steps:
 
1. 	Download Eclipse Modelling Tool (Neon version recommended): http://www.eclipse.org/downloads/packages/eclipse-modeling-tools/neon3
2. 	Open Eclipse and install Papyrus and Acceleo from “Help” Menu -> “Modeling Components”
3. 	Install “Papyrus MARTE profile” from “Help” Menu -> “Install Additional Papyrus Components”
4. 	Download and install the S3D plugin from the S3D download site.
 
Apart from the S3D core component, VIPPE and Essyn components are also required form MegaMart activities. In order to install both components, it is required to download them from the S3D downloading page and execute the corresponding makefiles.
 
System Requirements
  Linux OS
  Gcc compiler >= 4.8
  Libxml2
  Qt4
  Eclipse Neon Modelling Tools with the following plugins:
  Acceleo
  Papyrus
  Papyrus MARTE profile
  Llvm and SystemC are installed automatically
 
Release Notes
  Latest Release: 1.0.0
 
Review Description
This release extends previous CONTREP tool, and it provides new modelling capabilities to support complex communication semantics among components, specially oriented to handle different models of computation, and improvements in the management of the environment and hierarchy.
 
License
S3D is provided under a dual license. The components can be freely downloaded from the web page as binary or source code under a non-commercial, non-distributable license. Additionally, it can be licensed ad hoc, for further use. More details can be found in the downloading web page.
 
Support
We currently provide support through:
email: posadash@teisa.unican.es

2. Getting started guidelines

Documentation
Documents describing the S3D modeling methodology and a user guide can be found in the S3D website.
        	
Examples
Several examples are provided for downloading, based on a client-server system, showing how to model different mappings and different communications mechanisms with the S3D methodology.
 
3. Additional information

Research publications:
F. Herrera, J. Medina, E. Villar: "Modeling Hardware/Software Embedded Systems with UML/MARTE: A Single-Source Design approach", in S. Ha and J. Teich (Eds): "Handbook of Hardware/Software Codesign", Springer, 2017.
K. Grüttner, R. Görgen, S. Schreiner, F. Herrera, P. Peñil, J. Medina, E. Villar, et al.: “CONTREX: Design of embedded mixed-criticality CONTRol systems under consideration of EXtra-functional properties", Microprocessors and Microsystems, V.51, pp. 39-55, 2017.
F. Mallet, E. Villar, F. Herrera: "MARTE for CPS and CPSoS", in S. Nakajima, J.P. Talpin, M. Toyoshima and H. Yu (Eds.): "Cyber-Physical System Design from an Architecture Analysis Viewpoint: Communications of NII Shonan Meetings", Springer, pp.81-108, 2017.
H. Posadas, P. Peñil, A. Nicolás, E. Villar: "Automatic synthesis of embedded SW for evaluating physical implementation alternatives from UML/MARTE models supporting memory space separation", Microelectronics Journal, V.45, I.10, pp.1281–1291, 2014.

