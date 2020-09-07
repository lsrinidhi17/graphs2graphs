## Graph Conversion

The purpose of this exercise is to use basic Python data structures such as lists, dictionaries, and numpy's array.

I have implemented six different functions, listed below, to convert graphs represented in three different representations -- as lists of edges, as a dictionary of edges key'd by the from node to a list of to nodes, and as a matrix. The graphs will all be *directed*, which is to say that two edges are needed to get to and from two different nodes.

The three different graph types are:

- List: A list of tuples of edges, where each entry in the list is a tuple (from,to) where $from$ and $to$ are nodes.
- Dictionary: A dictionary where keys are $from$ nodes and the value is a *list* of $to$ nodes
- Matrix: A numpy matrix where each entry ($from$, $to$) that is a one represents an edge and a zero represents no edge.

