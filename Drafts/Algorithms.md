# Algorithms

## Sorting
<!-- Oversimplification -->

### Selection sort
https://www.khanacademy.org/computing/computer-science/algorithms/sorting-algorithms/a/selection-sort-pseudocode
1. Find the smallest card and swap it with the first card.
1. Find the next-smallest card and swap it with the second card.
1. Repeat until the array is sorted.

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
### BFS
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
