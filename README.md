# A-search-pathfinding-visualization
What is A* Search Algorithm? 
A* Search algorithm is one of the best and popular technique used in path-finding and graph traversals.

Why A* Search Algorithm? 
Informally speaking, A* Search algorithms, unlike other traversal techniques, it has “brains”. What it means is that it is really a smart algorithm which separates it from the other conventional algorithms. This fact is cleared in detail in below sections. 
And it is also worth mentioning that many games and web-based maps use this algorithm to find the shortest path very efficiently (approximation). 

 
Explanation 
Consider a square grid having many obstacles and we are given a starting cell and a target cell. We want to reach the target cell (if possible) from the starting cell as quickly as possible. Here A* Search Algorithm comes to the rescue.
What A* Search Algorithm does is that at each step it picks the node according to a value-‘f’ which is a parameter equal to the sum of two other parameters – ‘g’ and ‘h’. At each step it picks the node/cell having the lowest ‘f’, and process that node/cell.
We define ‘g’ and ‘h’ as simply as possible below
g = the movement cost to move from the starting point to a given square on the grid, following the path generated to get there. 
h = the estimated movement cost to move from that given square on the grid to the final destination. This is often referred to as the heuristic, which is nothing but a kind of smart guess. We really don’t know the actual distance until we find the path, because all sorts of things can be in the way (walls, water, etc.). There can be many ways to calculate this ‘h’ which are discussed in the later sections.

![a search 2](https://user-images.githubusercontent.com/52878265/185157383-be7168ae-83cd-4e0a-8f21-ef69602e4278.png)
![A search](https://user-images.githubusercontent.com/52878265/185157396-695a6ce2-6c32-4325-8baf-f8e1efbbe22b.png)
![astar 3](https://user-images.githubusercontent.com/52878265/185157405-09552fee-b809-4f69-b620-40885ae34c36.png)
![sc 4](https://user-images.githubusercontent.com/52878265/185157410-51df8144-8bcc-49c5-86bf-9168b64be0f2.png)
