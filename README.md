# Geometric-Lucas-Numbers
The first few Lucas numbers are

2, 1, 3, 4, 7, 11, 18, 29, 47, 76, 123, 199, 322, 521, 843, 1364, 2207, 3571, 5778, 9349

Attached code is a way to visualize Lucas numbers geometrically 


## Geometric Interpretation of Lucas Numbers

1. **Graph \( n \)-number of nodes on a unit circle.**
    - Place \( n \) nodes equidistantly around a unit circle.

2. **Count the edges around the unit circle.**
    - This will always be \( n \), corresponding to the number of nodes.

3. **Count the overall shape itself (or consider the empty set).**
    - This contributes 1 to the count, representing the entire \( n \)-gon or the empty set.

4. **Remove the counted edges and overall shape, then count the number of unique shapes that can be made with the remaining edges (essentially, diagonals).**
    - These are the edges that are not part of the original \( n \)-gon. They form unique shapes within the \( n \)-gon.

By following these steps, you end up with a count that aligns with the Lucas numbers \( L_n \) for the respective \( n \)-gons.

![image](https://github.com/jconorgrogan/Geometric-Lucas-Numbers/assets/130090573/087de08e-0f88-4f7b-8d25-371230cba8df)
