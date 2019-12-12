Space complexity: how much memory an algorithm needs

Time complexity: how much time an algorithm needs

We do care about time complexity, but how do we measure absolute time?

With the number of steps.

The algorithm's running time depends on the number of items of the input, the input size.

The order of growth: how the algorithm will scale and behave with the input size.

For us it is very important the connexion between the running time and the input size.

Linear time complexity

Our goal is ended up with an approximately linear algorithm in terms of the input. If the algorithm needs 1 ms to process 10 items, 2 ms for 20 items and 10 ms for 100 items it is a linear algorithm. If the third step take for example 100 ms it wouldn't be linear.

Asymptotic analysis

We only care about the big size inputs and we only keep the terms that grow fast as N becomes larger.

Complexity notations:

The big ordo notation (o)
Describes the running time in terms of the input size.

f(n) = O( g(n) )

f is the running time

n is the input size

2. Big omega notation

It describes the limiting behaviour of a function.

f(n) = Ω( g(n) )

3. Big theta notation

It describes the limiting behaviour of a function.

f(n) = Θ( g(n) )

Algorithms running times:

Factorial complexity(no good),

exponential complexity(no good),

polinomial complexity (no good),

linearithmic complexity (middle point),

linear time complexity (good)(for loop in one level array, searching, printing),

logarithmic complexity (good),

constant time complexity (best one)(swap variables).

Complexity classes:

P (polynomial),

NP (nondeterministic polynomial),

NP-complete (the hardest problems in NP),

NP-hard

Linear search

We have a one dimension array and want to search for a number.

Best case scenario: the first time item is the one we are looking for. O(1) running time.

Worst case scenario: the item is not in the array. O(N) running time.

Average case scenario: Item is uniformly distributed from the first index to the last index. O(N) running time.

Binary search

We want to find an item in an array, this time the array is sorted. We can use binary search only if the array is sorted.

If we know de index we can get it with O(1) constant time complexity.

If we don't know the index we can start at the middle, on every iteration we can discard half the items.

Binary search has logarithmic running time. O(logN)

Bubble sort

Repeatedely steps through the list to be sorted, compares each pair of adjacent items and swaps them if they are in the wrong order.

It is too slows and impractical.

Has quadratic running time O(N2).
