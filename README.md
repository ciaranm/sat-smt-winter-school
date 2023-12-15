Maximum Clique Instances for the SAT/SMT Winter School
------------------------------------------------------

The first line in the file is the number of vertices. Each subsequent line
specifies the two vertices involved in an edge. Vertices are numbered starting
from 1. For example, for this graph:

```
5
1 3
2 3
2 4
3 4
3 5
4 5
```

there are five vertices, and the largest clique has three vertices 3, 4, 5.

The random-5-*.graph instances should be a good starting point, and then
random-10-*.graph, and so on. The remaining instances are selected from the
DIMACS benchmark suite.
