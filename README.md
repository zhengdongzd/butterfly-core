# butterfly-core
We construct a new dataset of research collaboration network from [Aminer](https://www.aminer.cn/citation). It has 144,334 vertices, 1,821,930 edges, and a total of 7 vertex labels. 

Each vertex represents an author. The label of a vertex represents the main research field of the author, e.g., "Database", Machine Learning", "System", "Theory", "Data Mining", "Natural Language Processing" and "Computer Vision". For each vertex, we count on the author's published papers based on research topics. Finally, we take the research field of his/her most published papers as the vertex label.

There are three files under data folder. The "edges.txt" is the graph edge list, "vertex_to_field.txt" represents the vertex label and "vertex_to_name.txt" is corresponding the real author mame.
