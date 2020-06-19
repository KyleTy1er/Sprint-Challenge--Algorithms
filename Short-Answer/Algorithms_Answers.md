#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.
````
## Exercise I

# O(n) because the # of operations scales linearly with n...
# whatever value n is determines how many times the while loop runs
````
a)  a = 0
    while (a < n * n * n):
      a = a + n * n
````
b)

# O(n log n) – Linearithmic Time because the # of operations
# does not scale quadraticcaly O(n^2) or linearly O(n)
# but somewhere in between... O(n log n)
````
b)  sum = 0
    for i in range(n):
      j = 1
      while j < n:
        j *= 2
        sum += 1
````
c)
````
# O(n) ... because # of operations = n. For example if your n is 3,
# you will make 3 function calls.

c)  def bunnyEars(bunnies):
      if bunnies == 0:
        return 0

      return 2 + bunnyEars(bunnies-1)
```

## Exercise II

  
    complexity is o(2^n) because the function calls
    increase exponentially with n

   
    
 def egg_drop(n, f):
 
    #base case for recursion:
      
    if on the first floor try once
    if ground floor no attempt needed
    
    if (f == 1 or f == 0): 
        return f
  
    # We need f trials for one egg  
    # and f floors 
    if (n == 1): 
        return f 
  
    min = sys.maxsize 
  
    min of all values from 1st
    floor to fth floor + 1 
    for x in range(1, k + 1): 
        
        # recursive call to repeat function
        for each floor
  
        res = max(egg_drop(n - 1, x - 1),  
                  egg_drop(n, k - x)) 
        if (res < min): 
            min = res 
  
    return min + 1



