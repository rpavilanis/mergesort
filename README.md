# Assignment: Writing Mergesort

The recursive part of this problem is short -- happening only in the mergesort method, but driving the entire algorithm.

The `split_array` method is not mandatory to use, but I think it makes the solution a little easier to read and follow by making the `mergesort` method read almost exactly like the psuedocode, hiding all the details of how it works in other methods.

The hardest part of this problem is writing the combine method and dealing with all the cases that occur when combining two lists of sorted numbers. **This part is iterative, not recursive.**
