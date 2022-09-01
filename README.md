# A*-search-pathfinding-visualization
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
h = the estimated movement cost to move from that given square on the grid to the final destination. This is often referred to as the heuristic, which is nothing but a kind of smart guess. We really don’t know the actual distance until we find the path, because all sorts of things can be in the way (walls, water, etc.). 








![Screenshot (4)](https://user-images.githubusercontent.com/52878265/187992102-9dbbc481-d7ec-48a5-9cdb-23c47f1738ba.png)
![Screenshot (5)](https://user-images.githubusercontent.com/52878265/187992110-b841b119-b373-4f18-8415-cee5a62ac6d7.png)
![Screenshot (6)](https://user-images.githubusercontent.com/52878265/187992116-b319af37-8b97-4fc6-b96c-d596d7866724.png)
![Screenshot (7)](https://user-images.githubusercontent.com/52878265/187992118-4ccc5ca5-3217-476c-b8e2-3056f96d8262.png)
![Screenshot (8)](https://user-images.githubusercontent.com/52878265/187992122-e509e3d2-85a1-4084-a0d6-736379797f35.png)
![Screenshot (9)](https://user-images.githubusercontent.com/52878265/187992126-7adacd72-a9b5-40c0-841b-091f3087440b.png)
![Screenshot (10)](https://user-images.githubusercontent.com/52878265/187992131-9d5676a6-19f4-4d7f-a286-998e1d3e3302.png)
