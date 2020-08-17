#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The runtime complexity is 0(n). Because for me, you split it into 2 sections: a = a + n * n, so 'a' and the 'n * n'. First we find the fastest growing term (which is n * n, since 'a' is only a constant) and then second we take out the coefficient (which is n) leaving just 'n'... 0(n) Also I have noticed while loops tend to be 0(n) :) 


b) The runtime complexity is 0(n^2). Because we have a loop inside of another loop that are both 'n' based. So it would be n * n (or n^2)


c) The runtime complexity is 0 (n). Because the function will only return 1 less than it was before, so it will only run as many time as it is given.

## Exercise II

Lets do a Binary Search Tree.

If an egg is dropped less than the f floor, we will start at a floor be half of the buildings height. 
n // 2

And if the egg breaks at this point, we put f (for floor) : false - since it failed on the fall. Then do f divided by 2 (for half the building size) : To the right of the tree
f // 2

But if the egg doesnt break we will have a {f: true} then add up (n + f) // 2(which is the top half of the building): To the left of the tree

Then we have to repeat this proces until the BST returns true. 


