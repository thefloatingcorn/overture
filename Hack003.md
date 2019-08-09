# Coding Smart

## Python Tips
list.copy()

##recursive/searching

```Python
def getAllChildrenFromIdList(idList):
    childernIdList = []
    toProcessIdList = idList
    while toProcessIdList != []:
        thisId = toProcessIdList.pop()
        childernIdList.append(thisId)
        itsChildern = dict_ParentId_ChildrenIdList.get(thisId)
        if itsChildern != None:
            toProcessIdList.extend(itsChildern)
    return list(set(childernIdList))
```
