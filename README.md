# dismathportfolio-chvzadrian
dismathportfolio-chvzadrian created by Classroom for GitHub

# Week 1

- We were introduced to the subject DISMATH which is like a logic subject

- I learned the basics of DISMATH which are statements and proof

- I learned that truth is dependent to its holder. That DISMATH only deals with the mathematical truth

- I learned the symbols and usage of logical connectives such as negation, conjunction, disjunction, etc.


# Week 2 

- I also learned the corresponding truth table for each logical connectives 

- I learned laws for logical equivalences and proving using the truth table

- The absorption law is a combination of the other laws

- I learned that I can use either logical equivalences or truth table to simplify a logical statement


# Week 3

- We started discussing the different ways and methods of proof to solve/simplify a statement 

- To prove using these different methods of proof, we use the definitions of proven theorems or laws

- The first method we discussed is direct proof
  * Direct proof : in a conditional statement where p -> q, assume p is true and show that q is also true
  
- The next method we discussed is proof by contraposition
  * Contraposition : we show that not q is true then show that not p is also true

- The last method we discussed are vacuous and trivial proof
  * Vacuous : show that p is false , because p -> q is true when p is false
  * Trivial : show that q is true, it follows that p -> q must be also true
  
  
# Week 4

- We continued discussing the different methods of proof

- The method of proof that we discussed is proof by contradiction
  * Contradiction : assuming that not p is true, there will be a contradiction to the statement
  
- The last method of proof that we discussed is proof by equivalence
  * Equivalence : we prove a biconditional statement p <-> q by showing that p -> q and q -> p is true
  
- We finished discussing the different methods of proof, we then proceed to mathematical induction

- Mathematical induction means that if one case is true then the next case is also true or any particular case in a sequence


# Week 5

- We resumed in discussing mathematical induction and we were taught on how to solve problems involving mathematical induction

- There are 2 steps in order to solve a problem involing mathematical induction. First is the basis step and the next is the inductive step
  * Basis step : show that P(k) is true
  * Inductive step : show that P(k+1) is also true
    * if P(k+1) is true whenever P(k) is true, then P is true for all positive integer

- We reviewed the summation and sequences which was taught in engalg

- We were then introduced to the definition of recursive/inductive
  * Basis step : Specify the value of the function at zero
  * Recursive step : Give a rule for finding its value at an integer from its values at smaller integers
  
- We were introduced to recursive algorithms
  * Recursive algorithm : solves a problem by reducing/simplifying  the input values with a smaller input

- We were introduced to program correctness
  * Program correctness: This is the way to see if the algorith we created works the way we wanted it to work
  * We use proofs in order to show that the program works or gives the correct output
  
  * There are two parts in order to prove the correctness of a program:
  * 1. Partial correctness - we show that the correct answer will be obtained if the program terminates
  * 2. Next is to show that the program will always terminate

- We were introduced to the principle of inclusion and exclusion


# Week 6

- We were introduced to power series where we make represent a power series that is equivalent to the function given

- Not all functions can be expressed as power series, but most common and useful functions can.

- We were next introduced to sets
  * Set : it is an unordered collection of distinct objects that can be anything
    * Empty set : it contains no element - {} = 0
    * Membership : if the element is in the given set then it is a member of the set
    * Set builder notation : {x | some propert of x satisfies }

- We reviewed the venn diagram and we were taught the different kinds of venn diagram
    * Union : All of the elements of A and B is included
    * Intersection : The element present both in A and B
    * Difference : The elements in A that is not present in B
    * Symmetric Difference : The elements in A and B that is not present in the other set

- There are identities in sets:
  * Identity laws
  * Domination laws
  * Idempotent laws
  * Complementation laws
  * Commutative laws
  * Associative laws
  * Distributive laws
  * De Morgan's laws
  * Absoption laws
  * Complement laws
  
- These laws are in someway similar to logical equivalences we tackled in the previous lessons
  
- We were introduced to functions and its different types which are : 
  * One to one function
  * Onto function
  * Bijection
  
  
# Week 7 

- We were introduced to a new lesson which is algorithm

- We learned that algorithm is one of the useful in our world today

- Algorithm is a finite set of precise instructions for performing a computation or for solving a problem

- An example of an algorithm is finding the maximum/minimum element

- Pseudocode is a way of representing programming language in to simple human language

- Precondition are the statements that describe the valid input while postconditions are the conditions that the output should satisfy when the program has run


# Week 8

- We were next introduced to the properties of Algorithm
  * Input : an algorithm has input values from a specified set
  * Output : for each set of input algorithm it will produce an output value from a specified set
  * Definiteness : the steps of algorithm must be defined precisely
  * Correctness : an algorithm must output the correct values for each input values
  * Finiteness : the desired output should be obtain in finite number of steps
  * Generality : it should be applicable for all problems with the same form

- We were next introduced to searching algorithms which are:
  * Linear Search : it will inspect all of the elements in the set until it finds what it is looking for
  * Binary Search : it will divide the set of elements in to two then eliminate one part until it is left with the element it is looking for

# Week 9
- We continued discussing algorithm and we were introduced to sorting algorithm
- Sorting alogirthm is used when you want a list of elements to be ordered in increasing order
- The next algorithm that was taught to us was sorting alogrithm which are :
  * Bubble sort : comparing adjacent elements with each other and intercahnge the elements if they are in the wrong order
  * Insertion : compare the first element with the second, if the second is smaller place before the first and place it after if it is larger than the first element
- We were also introduced to greedy algorithm
 * A greedy algorithm gets to most preferred choice after every step
 * An example of this algorithm is the greedy change algorithm where it chooses the least coins needed to obtain a certain value

# Week 10
- This week we were introduced to a new lessons which is the growth of functions
- Growth of functions is described using big O-Notation
- The follwing are the common big O Estimates from greatest to least:
 * n!
 * 2^n
 * n^2
 * n log n
 * n
 * log n
 * 1
- Since the big-O notation does not provide lower bound we use:
 * Big-Omega notation - lower bound
- If we need both lower bound and upper bound we use:
 * Big-Theta notation - both for lower bound and upper bound
- We then discussed the Alogirthm time complexity:
 * Algorithm time complexity - it can also be expressed how many operations were used in the algorithm
 * Number of comparisons - what we used in order to measure the time complexity of the algorithm
- Complexity of Alogrithms:
 * Big-Theta 1 : Constant complexity
 * Big-Theta log n : Logarithmic complexity
 * Big-Theta n : Linear complexity
 * Big-Theta n log n : n log n complexity
 * Big-Theta n^b : Polynomial complexity
 * Big-Theta b^n, where b > 1 : Exponential complexity
 * Big-Theta n! : Factorial complexity

- The next lesson was division and modulo operator in algorithm
- We were familiar already with division and modulo since we already took up ENGALG1
- One of the applications of divison and modulo operator in algorith is cryptology which is the study of secret messages

# Week 11
- NO CLASS

# Week 12
- We were introduced to graphs and graphs theory
 * Graph - is a discrete structures that contain vertices and edges
 * Edges - connects the vertices
- Applications of graphs in real life are social network, PCB design, etc.
- Here are the basic terminologies we need to know about grahps:
 * Degree - number of edges incident with it, a loop is counted as 2
 * Isolated - 0 degree
 * Pendant - 1 degree
- We were also introduced to handshaking theorem
 * Equation : 2e = Summation of (deg)(v)
- There are also types of graph which are : 
 * Simple graph - contains exactly one edge between each pair of distinct vertices
 * Cylce - Cn, n>=3, consists of n vertices V1,V2... and edges {V1,V2} {V2,V3}...
 * Wheels - We obtain a wheel if we connect a cycle with all its vertices to another vertex inside of it
- There are also operations in graphs which are subgraph and union

- We were also taught of paths and circuits of graphs:
* Path - sequence of edges that begins at a vertex and travels from vertext to vertex along the edges
* Circuit - when you at the vertex where you have started
- We were next introduced to Euler and Hamilton graphs
- What we need to rember is that:
 * Euler - edges
  - Euler path - travels every edge of the graph exactly once
  - Euler circuit - travels every edge of the graph exactly once and go back to the starting vertex
  - Eulers formula: regions = edges - vertices + 2 
 * Hamilton - vertex
  - Hamilton path - travels to every vertex of the graph exactly once
  - Hamilton circuit - travels to every vertex of the graph exactly once and go back to the startix vertex
  
- We were introduced to the comparison of two graphs which is isomorphism
* Isomorphism - if there is a one-to-one and onto function from the vertices of the graph

- We also discussed planar graphs, homeomorphic graphs and Kuratowski's theorem:
 * Planar graphs - graphs that can be drawn without edges having to cross
 * Homeomorphic grahps - if they can be obtained from the same graph by a sequence of elementary subdivisions
 * Elementary Subdivisions - If a graph is planar, so will the graph obtained by removing an edge and adding a new vertex
 * Kuratowski's Theorem - a graph is nonplanar if and only if there is a subgraph homeomorphic to the following graphs

# Week 13
- This is our last lessons for this term
- We were introduced graph coloring
- Coloring a graph is assigning a color to a vertex of the graph without having 2 adjacent vertex with the same color
 * Four color theorem - chromatic number of a planar graph is no greater than 4
- Our next lessons was trees
 * Trees - is a connected undirected graph with no simple circtuis
 * Rooted Tree - a tree in which one vertex has been designated as the root and every edge is directed away from the root
 * m-ary Tree - if a rooted tree has a internal vertex that has no more than m children; if a tree has a internal vertex with exactky m children
 * Ordered Tree - where the children of internal vertex are ordered
- We could also use tree in binary search
- An application of a tree as models are family tree, representing oraginizations, etc.

- Our last lesson for this term was Modeling Computation, Automata Theory/ Finite State Machines, Finite-State Machines with Output
 and Finite-State Machines with No Output
- It was similar to the english language and it is just like graphs




  

