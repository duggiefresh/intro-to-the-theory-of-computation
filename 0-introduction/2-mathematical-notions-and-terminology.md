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
