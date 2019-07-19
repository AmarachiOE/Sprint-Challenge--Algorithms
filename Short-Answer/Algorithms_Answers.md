Add your answers to the Algorithms exercises here.

**Exercise 1:**

a) *O(n)* - This algorithm is ultimately running 1 loop with an equation. A single loop has a time complexity of O(n) or linear time, which takes dominance over the equation time complexity of O(c) or constant time.

b) *O(n^3)* - This algorithm contains a nested for loop of 4 levels. Each loop should have a time complexity of O(n), resulting in total time complexity of O(n^4). However, the last loop will actually run a constant number of times (10 times), resulting in its time complexity of O(c). Therefore, the time complexity of this algorithm is O(n^3)

c) *O(n)* - This algorithm contains 1 recursion. A single recursion results in a time complexity of O(n).

**Exercise 2:** 


- Number of stories = n
- Number of eggs = big number  -- important??
- At >= floor F, egg breaks
- At < floor F, egg remains

```
def find_floor_f(n):
    # keep track of floors where egg breaks
    floor_tracker = {}

    
    # starting at floor 1 ending at highest floor in n
    for floor in range(1, n+1): 
        drop egg method()  # returns T/F if egg broke

        # if drop egg method returns True (egg broke)
        # add that floor to floor_tracker dict

        if egg breaks: 
            floor_tracker[floor] = "egg broke"

    if floor_tracker == empty: # if floor_tracker never changes, the egg never broke...
        print(f"Egg never breaks")

    return first element in floor_tracker

```
Runtime Complexity = O(n) 
