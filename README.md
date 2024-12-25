# network-insights-with-gephi <br>
 Network analysis, visualization and gathering insights with gephi software <br><br>

### <ins>Twitter-followers-project:</ins> <br>
**nodes-size** : degree <br>
**pagerank** : to determine who are the most influential/important individuals in the twitter network. <br>
**communities** : to identify communities where nodes within a community have similarities between themselves. <br>

#### Force directed layout algorithms config:
|***Fruchterman Reingold***|***Force Atlas 2***|
|:------------:|:------------:|
|**Area** : 10000.0|**Scaling** : 10|
|**Gravity** : 10.0| **Gravity** : 1.0|
|**Speed** : 10|**Prevent overlap** : True|


### <ins>Mapping-Letters-over-Europe:</ins> <br>
**nodes-size** : degree <br>
**betweenness-centrality** : To identify nodes that occur most frequently along the shortest path between any two given nodes. <br>
**communities** : To identify communities where nodes within a community have similarities between themselves. <br>
**in-degree** : To identify which nodes are connected to more recipients. <br>

#### Force directed layout algorithms config:
|***Fruchterman Reingold***|***Force Atlas 2***|
|:------------:|:------------:|
|**Area** : 10000.0|**Scaling** : 50|
|**Gravity** : 10.0| **Gravity** : 1.0|
|**Speed** : 10|**Prevent overlap** : True|

### <ins>Chinese Biographical Database</ins> <br>
**nodes-size** : degree <br>
**betweenness-centrality** : which person occurs most frequently(common ancestry) between any two given persons. <br>

#### Force directed layout algorithms config:
|***Fruchterman Reingold***|***Force Atlas 2***|
|:------------:|:------------:|
|**Area** : 10000.0|**Scaling** : 50|
|**Gravity** : 10.0| **Gravity** : 40|
|**Speed** : 10.0|**Prevent overlap** : True|


### <ins>Diseasome</ins> <br>

#### Force directed layout algorithms config:
|***Fruchterman Reingold***|***Force Atlas 2***|
|:------------:|:------------:|
|**Area** : 10000.0|**Scaling** : 30|
|**Gravity** : 10.0| **Gravity** : 20|
|**Speed** : 8.0|**Prevent overlap** : True|

**note:** some of the insights have been derived before applying force-atlas-2, they have been mentioned below.<br>

**node-size** : Degree.<br>
**communities** : Which diseases appear together in a community based on their similarity of interaction with other diseases. <br>
**communities node labels** : Nodes with in-degree of 6 and above, to make the labels more readable. <br>

Now apply the force-atlas-2 algorithm (remove all filters previously used).<br>

**node importance** : With community colours enabled, change the node size from degree to pagerank. This is to highlight which set of diseases are most popular/important in the network.<br>

**betweenness centrality** : Make the size of the node as betweenness centrality and the colour of the nodes as their pagerank score. It turns out that there
is a positive correlation between betweenness-centrality and pagerank score. The nodes which occur frequently between shortest path between any two nodes often tend to have a good pagerank score. 


