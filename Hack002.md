# Lovely Bugs

## Python For Loop

Python provides a kind of easy-to-use 'For Loop'.
Let's have a look on an example script:
```Python
animals = ["Tom", "Jerry", "Meerkat", "Bird", "Dog"]
animals_away_list = ["Jerry", "Meerkat"]
for animal in animals:
    if animal in animals_away_list:
      animals.remove(animal)
print(animals)
```

For the example script, the output is expected to be: ['Tom', 'Bird', 'Dog'].
However, the actual output is: ['Tom', 'Meerkat', 'Bird', 'Dog'].
The reason is that example script is equivalent to the following script:
```Python
animals = ["Tom", "Jerry", "Meerkat", "Bird", "Dog"]
animals_away_list = ["Jerry", "Meerkat"]
for index in range(len(animals)):
    animal = animals[index]
    if animal in animals_away_list:
        animals.remove(animal)
        # will skip Meerkat after removing Jerry
print(animals)
```
