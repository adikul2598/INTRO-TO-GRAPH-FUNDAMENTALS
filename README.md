# INTRO-TO-GRAPH-FUNDAMENTALS

## Graph Database and Analytics
A graph consists of vertices (also called nodes) which are connected by edges. All the vertices and edges make a schema.  

 The nodes and edges can have properties or attributes, such as age, location, time, etc., which provide details about each node and edge; graphs with nodes, vertices, and properties are called property graphs.  
 
Graphs can be used as a referral network by searching for different entities which have multiple vertices in common and are a few hops (or edges) away. 

Property graphs contrast from Resource Description Framework (RDF) Graphs because each node on an RDF is a Unique Resource Identifier (URI) which cannot carry any attributes.  

## Managing Relationships

 Relational databases stores each entity in separate tables which then require table joins to connect, an action which could take hours and are computation expensive.  
 Graph databases, in contrast, are one, single, pre-connected table. They’re a natural storage model built for storing and analysing relationships. Because all of its relationships are first-class entities, graph databases, optimised for deep analytics, tend to be much faster than relational databases.
 
 graphs are good for dealing with relationships and are the only of the said structures which manage relationships well, but not all graphs offer real-time speed at scale  
 
 ## Types of Graph
 
There are currently three types of graph: Graph 1.0, Graph 2.0, and Graph 3.0. 

Graph 1.0 using native graph storage with a single server and non-parallel architecture

 Graph 2.0 uses a NoSQL base for storage scale and can support two hops queries, but they aren’t designed for real-time updates  
 
 Graph 3.0, however, is both native and parallel, supporting over ten hops and taking less time to run hops and load data  
 
 ## DATA SCIENCE CAPABLITIES
 
 Deep Link Analysis supports looking through data with more than three hops. This can grow exponentially. An example of Deep Link Analysis is trying to find a user’s fraudulent history. 
 
 Multi-dimensional Entity and Pattern Match will look for a pattern within a graph  
 
 Relational Commonality looks for something in common with two vertices, like common customers for two vendors.  
 
 Hub Community Detection searches for the most influential vertex in a graph, the vertex with the most edges. This can help find the relevance of something within a community.  
 
 Geospatial Graph Analysis shows how close two things are to each other using latitude and longitude.  
 
 Temporal Graph Analysis is similar, but it looks at how entities and relationships change over time.  
 
 Machine Learning and Explainable AI can be used by graph by extracting features and using GraphStudio (the GUI) to provide visual aids for the graphs.  
