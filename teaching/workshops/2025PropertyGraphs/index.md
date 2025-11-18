# Transforming Data into Property Graphs with Graflo, Neo4j & ArangoDB

Practical Workshop by [**Alexander Belikov**](https://alexander-belikov.github.io/)

This tutorial introduces property graphs as a powerful framework for structuring and analyzing complex data. Participants will learn how to transform tabular (CSV) and hierarchical (JSON, XML) datasets into graph form using Graflo, and ingest them into Neo4j and ArangoDB. We will cover the fundamentals of property graphs, schema design, and querying, alongside practical applications such as community detection and preparing graphs for graph neural networks. Through hands-on exercises, each participant will create a schema for a dataset of their choice and deploy it in a graph database, gaining practical skills in graph modeling and analytics for research and applied domains


**Place**: Laboratorio de Ciencias de la Computación 2.  Segundo Piso. Tlahuizcalpan. Facultad de Ciencias, UNAM.

**Time** Wed 19th November, 14:00 – 16:30 hrs.
We will start with a 15 minute space to check that everyone is setup and properly configured.

**Requirements** 
 * If possible, bring your own computer with [git](https://git-scm.com/install/) and [docker](https://docs.docker.com/engine/install/) installed.
 * Optionally, bring a dataset that you are interested in, or working on, that you'd like to see represented as a graph.
 

**To make things faster during the workshop** 

1. Install UV
```
curl -LsSf https://astral.sh/uv/install.sh | sh  
export PATH="$HOME/.local/bin:$PATH"  
uv version

```
2. Install GraphViz and PyGraphviz

MacOS: `	brew install graphviz   `
Debian/Ubuntu:  `sudo apt update && sudo apt install -y graphviz graphviz-dev  `

3. Pull arango and neo4j images

```
docker pull arangodb:3.11.13
docker pull neo4j:5.21.0

```


More info here:
https://gist.github.com/alexander-belikov/2e74bae0b6a2f4e3ef5edfb67d72371f



