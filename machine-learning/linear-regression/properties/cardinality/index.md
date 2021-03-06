---
layout: post
title: Cardinality of a Set
---


The cardinality of a set $$S$$, denoted by $$\vert S\vert$$, is the size of the set.  If a set is finie, then the cardinality of the set is the number of elements in the set.  If the set has an infinite number of elements, its cardinality is $$\infty$$. <br><br>

**Example 1:**
Let $$A = {1, 2, 3, 4}.$$ Then $$A$$ is a finite set with four elements, and $$\vert A \vert = 4 $$<br>

The concept of cardinality includes the base case where the set is empty, $$ S = \emptyset$$ and when the set contains an infinite number of elements.

**Example 2:**
The $$\emptyset = \{ \}$$ meaning that it is a finite set with no elements.  Thus $$\vert \emptyset \vert = 0$$ <br>

For many of the special sets, the cardinality of the set is infinity.  Even though some sets "seem" smaller than others, the sizes of the sets are equal.  Consider the example below where one set is contained in the other, a proper subset of the other.  The larger set contains what would seem twice as many elements as the smaller subset, but both sets are countably infinite.

**Exmaple 3:**
The set of positive integers, $$Z^+ = \{1, 2, 3, 4, ...\},$$ has an infinite number of elements in it's set so that  $$ \vert Z^+ \vert = \infty.$$ <br>
While $$E  = {...,-4, -2, 0, 2, 4, ...}$$ is the set of all even integers and  $$\vert E \vert = \infty.$$  A statement that can be proven to be true,  is: "There exists a rule that maps the set of positive integers to the set of even integers."  <br>


The cardinality of a set is a property of the set.  A property is a defining characteristic of the set, just as a person's height standing barefoot is a descriptive feature of a person.  As seen in Example 3, two sets can have the same cardinality but not contain the same elements just as two different people can be the same height.  

It is helpful to note that if there is some question about whether two sets are equal, looking at the cardinality of the two sets can help to address the problem. If we wanted to test to see if two web pages were the same, we could start by looking at the word counts for both pages.  If the word counts are not the same, then the pages are not exactly the same, equivalent.  

**Exmaple 4:**
We are given two sets, $$A$$ and $$B$$ and know that set $$A$$ has cardinality 5 and $$ \vert B \vert = 6$$. If we assume the set $$A$$ is the same as the set $B$, then every element that is in $$A$$ is also in $$B$$ and every element that is in $$B$$ is also in $$A.$$   For this to be true, the cardinality of $$A$$ is the same as the cardinality of $$B.$$  This contradicts what we are given to be true about the sets $$A$$ and $$B,$$ that $$\vert A \vert = \vert B\vert .$$  Meaning, the sets $$A$$ and $$B$$ are not equal.


*Note:* What we learned in Example 4 can be stated generally and will be used again and again. <br>
If there are two sets $$X$$ and $$Y$$,<br>
we say that the sets $$X$$ and $$Y$$ have the same cardinality and write $$\vert X \vert  = \vert Y\vert$$ when the number of elements in $$X$$ is exactly equal to the number of elements in $$Y.$$ In this case, there exists a (bijective function) map $$f$$ from the elements of  $$X$$ to the elements of $$Y$$ so that under this mpaping every element of $$X$$ and every element in $$Y$$ are "matched." <br><br>

**Exmaple 5:**
Let $$A = \{1,2,3\}$$ and $$U = \{cat,\ dog,\ walrus,\ elephant\}$$.  We intentially used the capitol letter $$U$$ for our second set so that it would evolk the idea of a Universal set.  It is clear that $$A$$ and $$U$$ are not equivalent sets,  However, there are smaller subsets of $$U$$ that have the same cardinality of $$A.$$ One example is the subset $$S$$ of $$U$$ defined by the rule  = the set of all elements x of $U$ that begin with either the letter 'c', the letter 'w' or the letter 'e.'  Then
$$ S = \{cat, walrus, elephant\}$$ 
and using our notation for subset (containment) $$S \subset U.$$  In our note, we mentioned that if two sets have the same cardinality, then there is a (bijective) mapping from one set to the other.  One way to define such a map is as follows:
$$\text{for }x \text{ in } A, \text{ map } x \text{ to the element }y \text{ in } S \text{ so that } y \text{ has } x \text{ number of syllables.}$$
$$1 \rightarrow cat$$
$$2 \rightarrow walrus$$
$$3 \rightarrow elephant$$
Other functions, mappings, are possible, but what is important to understand here is that one set represents a "domain" set of objects and the other set is the "target" set. The mapping of interest must clearly define a connection from each of the objects in the domain set one element in the target set and every target set element is matched to one domain element.  If the cardinalities of the domain and target sets are finite and not the same, this type of mapping is not possible.

When $$\vert X \vert < \vert Y\vert $$ for a sets $$X$$ and $$Y,$$ then the set $$X$$’s cardinality is less than the set $$Y$$’s cardinality. This occurs when number of elements in $$X$$ is less than or equal to the number of elements in $$Y$$. In this case, there exists a one - to - one (injective) function $$f$$ from $$X$$ to $$Y$$, but not a well-defined mapping from $$X$$ onto all of the set $$Y.$$ The often used imagery here is that the set $$X$$ contains pigeons and the set $$Y$$ is a collection of "pigeon holes." The mapping takes a pigeon and assigns the bird to a pigeon=hole in the set $$Y$$. There is one bird per pigeon-hole. Since we are assuming that there are more pigeon-holes than pigeons, there are some unihabited pigen-holes.  The mappings from $$X$$ to $$Y$$ will be 1-1(injective) but not onto (surjective).  <br><br>

If the set $$X$$ has more elements than the set $$Y,$$ then $$\vert X \vert > \vert Y\vert $$. That is the set $$X\text{'s}$$ cardinality is greater than set $$Y$$’s cardinality. Back to the pigeons and pigeon-holes. If we create a well-defined rule assigning to each pigeon exactly one pigeon-hole there will not be enough pigeon-holes for every bird to have it's own cubbie. Since there will be some sharing of pigeon-holes in order to house all of the birds, any map that we define from $$X$$ to $$Y$$ is said to be onto (surjective) but not 1-1 (injective).<br>



 |||[Index](../../../../)||| [Prev](../set-equality)||| [Next](../countable-and-uncountable)
 



