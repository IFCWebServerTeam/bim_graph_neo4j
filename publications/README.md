
# Publications
## Master thesis
*Title*: [Applying graph theory concepts for analyzing BIM models based on IFC standards](https://tu-dresden.de/bu/bauingenieurwesen/cib/ressourcen/dateien/publikationen/Projekt-_Diplomarbeiten/Masterarbeit_Ahmed_Nahar_2017.pdf)

*Author*: Ahmed Babkier Nahar

*Supervisors*: Prof. Raimar Scherer & Ali Ismail MSc.

*Period*: 06/2016- 01/2017

*Abstract:*

Labeled property graph models are a suitable way for representing and describing the vast amount
of information inside Building Information Models (BIMs). Where graph models can be
automatically generated based on data extracted from Industry Foundation Classes (IFC) models.
The aim of this master thesis is to study the potential of using graph databases and the concepts of
graph theory to manage, visualize and analyze the information inside BIMs. This can be done
through for example through applying data retrieval queries, applying pathfinding algorithms and
analyzing the complex relationships between the BIM model entities.

The IFC data model is used in the present study to build the graph database; therefore, a brief
background on IFC data schema architecture is presented to build-up basic understanding on how
IFC models are encoded. This is followed by an introduction to graph theory concepts and graph
databases, with the aim to investigate the capabilities of graph models in representing complex and
rich datasets such as BIM models.

The research proposes a generic approach to create two kinds of graph models: (1) IFC Meta Graph
(IMG) model based on the IFC EXPRESS schema and (2) IFC Objects Graph (IOG) model based
on STEP physical file format. The IFC EXPRESS schema is used as data source to generate the
IMG model to graphically represent the IFC classes and the relationships. The IMG model
expresses the classes and their attributes as nodes, and the relationships between them as edges.
While, the IFC objects model files are used to build the IOG models, where IFC data are extracted
through an IFC data model server and then imported into graph database management system
(www.neo4j.com).

In both cases of graph modeling, there is a need for a third-party system to enable the data
transmission process from the IFC schema/models to Neo4j database. Therefore, the IFC data
model server www.ifcwebserver.org has been used to generate the graph query statements scripts
and extract the IFC data in form of comma-separated values (CSV) data files for exportation into
the Neo4j graph database.

This is following by application of graph queries and filters to visualize and analyze building
information and to explore the capabilities of graph database in answering realistic questions in
building projects particularly. And secondly, to provide a tool for a comparison study of different
IFC standard releases or different IFC model versions, when a single graph database is used to
storage various IFC models. Finally, the graph model is used for indoor navigation applications in
buildings using spatial and geometric information extracted from the IFC model.
