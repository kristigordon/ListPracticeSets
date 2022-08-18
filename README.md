# ListPracticeSets

Learning how to use lists in Python to manipulate data and write bigger more intricate programs. 


<img width="584" alt="Screen Shot 2022-08-06 at 10 36 41 AM" src="https://user-images.githubusercontent.com/66803124/183253489-f3491908-cdb8-4f06-b4bd-a4aa06179a0a.png">

```
#Lists are ORDERED. []

high_scores = [99, 78, 56, 50, 20, 12]
#Common to have a list with one type of variable
#but this is not always the case

stuff = [4, 5.6, True, False, 'hi', []]
#Here we have int, float, bool, string and an empty list

list()
#will return: []
#You can also use the list function to create an empty list

list("hello")
returns: 
['h', 'e', 'l', 'l', 'o']
#very different than a string hello, this is a list. 

list(range(3, 10))
[3, 4, 5, 6, 7, 8, 9]
```

```
a[2 : 5] gives [4.63, True, "World"]
a[ : ] gives ["Hello", 1, 4.63, True, "World", 2.0, "False"]
a[-1: -3 : -1] gives ["False", 2.0]
```

```
a[1] = 2
print(a) gives ['Hello', 2, 4.63, True, "World", 2.0, "False"]
```
