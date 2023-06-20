- [Graph Theory](#graph-theory)
	- [Adjacency Matrix](#adjacency-matrix)
- [Digital Electronics](#digital-electronics)
- [Assembly Language](#assembly-language)

# Graph Theory
- Vertex/nodes + Edge
	- Identify set of vertices + identify set of edges
	- $E = V^2 \to \frac{V(V-1)}{2}$
- **Undirected graph** = an edge from `A` to `B` is the same as an edge from `B` to `A`
- **Directed graph** = an edge with a specified direction (one-way road)
- **Connected graph** = if there is a path from every vertex to every other vertex in the graph
- **Cycle** = path where the first and last vertex are the same (does not have to visit every vertex)
- **Weighted graph** = weight/cost associated w/ each edge

- **Tree** = graph w/ no cycles
	- **Only one** path between any two nodes
	- A tree w/ $N$ vertices has $N-1$ edges
- **Forest** = group of disconnected trees
- **Spanning tree** = subgraph that contains all the vertices and forms a tree
	- **Min. Spanning tree** = found for weighted graphs to minimize cost

## Adjacency Matrix
- Consider the **directed** graph:
![](Pasted%20image%2020230514000220.png)

- $N$ x $N$ grid
- $M^p (i, j)$, $p$ is the length of paths that can be counted

$M^1$
|-|A|B|C|D|
|-|-|-|-|-|
|A|0|1|0|1|
|B|0|0|1|1|
|C|0|1|0|0|
|D|0|0|1|0|

$M^2$
|-|A|B|C|D|
|-|-|-|-|-|
|A|0|0|2|1|
|B|0|1|1|0|
|C|0|0|1|1|
|D|0|1|0|0|


# Digital Electronics
- Circuit from logic gates, Boolean algebra
![](Pasted%20image%2020230514004140.png)
![](Pasted%20image%2020230514004157.png)
![](Pasted%20image%2020230514004207.png)

# Assembly Language
- Execution is sequential unless otherwise noted with **branch instructions**
- Result of each operation is stored in a special memory word, `ACC`
	- Initially `ACC = 0`
- Each line: `LABEL OPCODE LOC`
	- `LABEL` = alphanum. character string
	- `OPCODE` = reserved functional keywords
	- `LOC` = reference to a label OR **immediate data**
	- `LOAD A` would put contents referenced by label `A` into `ACC`
	- `LOAD=123` would store value `123` in `ACC`
![](Pasted%20image%2020230514004448.png)