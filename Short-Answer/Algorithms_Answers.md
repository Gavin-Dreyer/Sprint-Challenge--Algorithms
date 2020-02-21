#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The time complexity of 'a' is polynomial or O(n^c) because the input n is increased by a constant exponential of 3 or O(n^3).


b) The time complexity of 'b' is polynomial or O(n^2) because it contains nested iterations. If more iterations are nested, it would increase to O(n^3) or 0(n^4).


c)  The time complexity of 'c' is linear or O(n) because it is being called n times. As the number of n increases so does the number of tasks needed to recurse down to the base at a 1:1 ratio.

## Exercise II

I would use binary search to quickly find the floor at which an egg would not be broken. If f = 50, I would start at 25. If it breaks, I would go to f = 13. If it does break, go to f = 7. If it doesn't break, go to f = 19. I would continue this until I found the floor at which the egg will not break. Binary search has a runtime complexity of O(log n).