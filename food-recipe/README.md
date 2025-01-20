# Food Recipe Ontology and Knowledge Graph

## Ontology Development

TBD

## Graph Creation

![Food Recipes Ontology](Food%20Recipes%20Ontology.png)
See the corresponding JSON file [here](Food%20Recipes%20Ontology.json), which you can use to import in [arrows.app](https://arrows.app).

## Graph Schema

To import the graph schema into the [Neo4j](https://neo4j.com) graph database, follow these steps:

1. Open Neo4j Desktop and create a new project.
2. Start a new database or connect to an existing one.
3. Open Neo4j Browser.
4. In `arrows.app`, click on `Download/Export` and copy & paste the Cypher query language to the neo4j Browser to create the graph.

5. Use the command `call db.schema.visualization()` to visualize the schema.

Here is the schema visualization:
![Graph Schema](schema.png)

## Labeling Instruction Example

To ensure consistent labeling of recipe tags, here's an example of the instructions for our annotators in [Labelbox](https://www.labelbox.com): [Recipe Tags Refinement Instructions](Recipe%20Tags%20Refinement%20Instructions.pdf).
