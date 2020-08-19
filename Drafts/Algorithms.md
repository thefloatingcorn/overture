# Algorithms

## Sorting
<!-- Oversimplification -->

### Selection sort
https://www.khanacademy.org/computing/computer-science/algorithms/sorting-algorithms/a/selection-sort-pseudocode
1. Find the smallest card and swap it with the first card.
1. Find the next-smallest card and swap it with the second card.
1. Repeat until the array is sorted.

### Insertion sort
<!-- doing extra swaps -->

### Quick sort
https://www.tutorialspoint.com/data_structures_algorithms/quick_sort_algorithm.htm
1. Make the left-most index value pivot.
1. Divide the array using pivot value.
1. quicksort left partition recursively.
1. quicksort right partition recursively.

### Merge sort
https://www.khanacademy.org/computing/computer-science/algorithms/merge-sort/a/overview-of-merge-sort
1. Divide the array using midway index.
1. Sort the subarrays in each of the two subproblems created by the divide step.
1. Merge the two sorted subarrays back into the single sorted subarray.


## Searching

### Binary
```Python
l, r = 0, len(nums)
while l < r:
    m = l + (r-l)//2
    if nums[m] == target:
        return m
    if nums[m] > target:
        r = m
    else:
        l = m + 1
return l
```

### Breath-First
```Python
def getDistanceBFS(targetId, rootIdList):
    distance = 0
    if targetId in rootIdList:
        return distance
    else:
        seen = []  
        queue = []
        seen += rootIdList          
        queue += rootIdList
    while queue != []:
        distance += 1
        tempQueue = []
        for thisId in queue:
            childIdList = getChildIdList(thisId)
            for childId in childIdList:
                if childId == targetId:
                    return distance
                elif childId not in seen:
                    tempQueue.append(childId)
                    seen.append(childId)
        queue = tempQueue              
    return -1
```
