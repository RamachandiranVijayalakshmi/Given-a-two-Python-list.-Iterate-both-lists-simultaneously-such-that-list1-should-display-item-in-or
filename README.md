## Given-a-two-Python-list.-Iterate-both-lists-simultaneously-such-that-list1-should-display-item-in-or
## Sample code to check the details
```sh
list1 = [10, 20, 30, 40]
list2 = [100, 200, 300, 400]

for x, y in zip(list1, list2[::-1]):
    print(x, y)
```
## Example Output
10 400
20 300
30 200
40 100
