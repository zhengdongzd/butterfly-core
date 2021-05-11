# butterfly-core
We construct a new dataset of research collaboration network from Aminer~\footnote{\scriptsize{https://www.aminer.cn/citation}}~\citep{tang2008arnetminer}. It has $144,334$ vertices, $1,821,930$ edges, and a total of $7$ vertex labels. Each vertex represents an author. 
 %The label of a vertex represents the main research field of the author, e.g., ``Database'', ``Machine Learning", and so on. 
For each vertex, we count on the author's published papers based on research topics. Finally, we take the research field of his/her most published papers as the vertex label, e.g., ``Database'', ``Machine Learning'', ``System'' and so on.
