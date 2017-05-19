# Pascall's triangle


1
2
3
4
5
6
    1
   1 1
  1 2 1
 1 3 3 1
1 4 6 4 1
   ...

The numbers at the edge of the triangle are all 1
each number inside the triangle is the sum of the two numbers above it. 

We will write a recursive function to solve this problem

```scala
def pascal(c: Int, r: Int) : Int = {

}

```

## Make a base case
- we need to make sure it doesn't recurse forever
- if the numbers on the ends are all one, we know that if the coloumn has a zero
