# Graph_Database
Transforming the traditional relational database into graph database for more efficient querying and data science algorithms exploration. With Neo4J and Cypher.
![Screenshot 2023-05-27 160019](https://github.com/coffeemartin/Graph_Database/assets/73702415/01853908-f420-4b09-ade4-4825086dcd2b)


The graph database project is a continuation of the data warehousing project, the same data set was used to build the graph database.
The design, ELT process, queries have all been updated from the previous relational database, in order to suit the purposes of property graph database and answer different business queries.
In comparison with traditional SQL databases, graph database has its unique capabilities:
1. Relationships: comparing with traditional SQL databases, where any relationships are presented through fact/dimension tables, and single/multiple joins, the graph database has much better and
intuitive way to represent relationships. Especially with many-to-many relationships, there is no extra bridging table needed, any relationship can be easily added/deleted. It is also able to naturally model
the real-world scenarios, such as social network, supply chain, fraud detection etc where involves complex relationships, much easier to represent to the wider range of audiences who has limited
knowledge of traditional databases and domain knowledges.
2. Performance: Graph database has superior performance on queries, it only query the part of the graph paths where satisfy the query, as a result, graph database can perform complex and deep ‘joins’
and traversals through nodes and relationships, this makes graph database suitable for scenarios where relationships are critical and performance is paramount.
3. Schema free or flexible: Graph database structure can be easily modified and updated without specifically changing the schema, this is super beneficial in current fasting evolving modern world. Graph
database do not need follow the ACID principle
4. Algorithms: Graph database provide powerful packages and algorithms for analytics and data explorations. In Neo4j Graph data science library, the algorithms including centrality, community
detection, similarity, path finding, etc can be easily used to solve complex queries and reveal deep knowledge of the data. For example, what’s the best path for police force to patrol through a city? Or
revisit the previous crime site based on weighted importance of the crime cases? How much similarity different suburbs have in terms of population, crime rate? These can be extremely difficult or
impossible to achieve in traditional database. The COLLECT, UNWIND, PATTERN COMPREHENSIONS are also extreme powerful syntax to work with lists.
5. Graph database do not need NULL value has a placeholder like in tabular form, if no information is provided, then no property, relationship will be needed.
![Screenshot 2023-05-28 124500](https://github.com/coffeemartin/Graph_Database/assets/73702415/1eb06797-b282-41df-917f-257efbd7e03c)
