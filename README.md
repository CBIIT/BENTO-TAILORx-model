![Build Status](https://github.com/CBIIT/BENTO-TAILORx-model/actions/workflows/model-test-and-deploy.yml/badge.svg)


BENTO-TAILORx Data Model
====

The Bento Core Data Model supports the Bento software framework that has been developed to stand up data sharing platforms
for clinical trials and research programs. Modern clinical trials and research programs generate large volumes of complex
biomedical data types. To address this complexity, the Bento Core Data model uses a graph structure to model a clinical trial workflow. 
Key trial entities are modelled as node types, while the association between nodes are explicitly modelled as relationship types. 

The Bento Core Data Model has been extended to fit the TAILORx clinical data set. The extended model, also called the BENTO\_TAILORx 
data model, is comprised of 20 node types and 37 relationship types. Both nodes and relationships store data attributes in the 
form of properties. The BENTO\_TAILORx graph data model has been implemented in the community edition of Neo4J, 
a commercial graph database platform.

[View on Github Pages](https://cbiit.github.io/BENTO-TAILORx-model/)
