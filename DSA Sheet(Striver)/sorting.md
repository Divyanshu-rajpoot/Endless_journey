# Sorting

## Selection Sort

in this sorting algo we find the first the `smallest` element in the array and replace it will the current position of index `i`
we loop through the array `n-2` times and find the smallest element in the array

### java code

```java
    for(int i= 0;i<=n-2;i++){
        int min = i;
        for(int j = i;j<n;j++){
            if(arr[j]<arr[min]){
                min = j;
            }
        }
        //simple swap operation
        int temp = arr[j];
        arr[j] = arr[i];
        arr[i]= temp
    }
```

#### time complexity

worst -> O(n2)

best -> O(n2)

Avg -> O(n2)

-----

## Bubble Sort
