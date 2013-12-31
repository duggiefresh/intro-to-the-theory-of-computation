# Mathematical Notions and Terminology

## Sets

A **set** is a group of objects represented as a unit. Sets can contain any type
of object: numbers, symbols, and even other sets. The objects in a set are called
**elements** or **members**. Sets can be described formally in many different ways.

```
S = {7,21,57}
```

* &isin;: denotes set membership
  * 7 &isin; {7,21,57}
* &notin;: denotes set nonmembership
  * 8 &notin; {7,21,57}

For two sets *A* and *B*, then *A* is a **subset** of *B*, written *A* &sube; *B*,
if every member of *A* is also is a member of *B*. We say that *A* is a **proper
subset** of *B*, written *A* &#8842; *B*, if *A* is a subset of *B* and not equal
to *B*.

A set's order or repetition of its members does not matter. We get the same set *S*
by writing {57,7,7,7,21}. If we do want to take the number of occurrences of members
into account, we call the group a **multiset** instead of a set.a Thus {7} and {7,7}
are different as multisets but identical as sets. An **infinite set** contains infinitely
many elements. For infinite sets, use "..." to denote "continue the sequence forever."

We can write the set of **natural numbers**, &#8469; as: {1,2,3, ...}

The set of **integers**, &#8484; as: {..., -2,-1,0,1,2, ...}

The set with zero members is called the **empty set** and is written &empty;. A set
with one member is called a **singleton set**, and a set with two members is called
an **unordered pair**.

To describe a set containing elements according to some rule, we write
{*n* | rule about *n*}. Thus {*n* | *n* = *m*<sup>2</sup> for some *m* &isin; &#8469;}
means the set of perfect squares.

Let's imagine two sets, *A* and *B*:

* **Union**: is the set we get by combining all elements in *A* and *B* into a single set.
* **Intersection**: a set of elements that are both in *A* and *B*
* **Complement**: a set of all elements under consideration that are *not* in *A*.

## Sequence and Tuples

A **sequence** of objects is a list of these objects in some order, usually noted as
a list within parentheses, `(7,21,57)`. Order does not matter in a set, however, in a
sequence it order does matter. `(7,21,57)` is not equal to `(21,7,57)`. Repetition
does matter in a sequence as well.

Sequences, just like sets, may be finite or infinite. Finite sequences are called
**tuples**. A sequence with *k* elements is called a **k-tuple**, so `(7,21,57)` is
a 3-tuple. A 2-tuple is also known as an **ordered pair**.

Sets and sequences may appear as elements of other sets and sequences. For example,
the **power set** of *A* is the set of all subsets of *A*.

If *A* and *B* are two sets, the **Cartesian product** or **cross product** is written
as *A x B*, where the set of all ordered pairs wherein the first element is a member of
*A* and the second element is a member of *B*.

```
A = {1,2}
B = {x, y, z}
A x B = {(1,x),(1,y),(1,z),(2,x),(2,y),(2,z)}
```

## Functions and Relations

A *function* is an object that sets up an input-output relationship.

* **Domain**: a set of possible inputs to the function.
* **Range**: outputs of a function that come from a set
* **Unary function**: given name to a function with one argument.
* **Binary function**: given name to a function with two arguments.

## Graphs

* **Undirected graph** or **graph**: is a set of points with lines connecting some
of the points, also known as *nodes* or *vertices*. Connecting lines are known as
*edges*.
* **Degree**: the number of edges at a particular node.
* **Subgraph**: a graph that contains nodes that are a subset of another graph's nodes,
likewise for its edges..
* **Path**: a sequence, within a graph, of nodes connected by edges.
* **Simple path**: a path that doesn't repeat any nodes. A graph is *connected* if every
two nodes have a path between them.
* **Cycle**: a path that starts and ends in the same node.
* **Simple cycle**: one that contains at least three nodes and repeaats only the first
and last nodes.
* **Tree**: a graph that is connected and has no simple cycles.
* **Directed graph**: a graph that has arrows instead of lines
  * *outdegree*: arrows pointing out from a particular node.
  * *indegree*: arrows pointing into a particular node.

## Strings and Languages

* **Lexicographic order**: same as the familiar dictionary order.

## Boolean Logic

**Boolean logic** is a mathematical system built around the two values *TRUE* and
*FALSE*. We can manupulate Boolean values with *Boolean operations*.

* **Negation**: *NOT*
* **Conjunction**: *AND*
* **Disjunction**: *OR*
* **Exclusive or**: *XOR*
* **Equality**
* **Implication**
