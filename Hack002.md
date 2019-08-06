# Lovely Bugs

## Python For Loop

A script:
```Python
animals = ["Tom", "Jerry", "Meerkat", "Bird", "Dog"]
animals_away_list = ["Jerry", "Meerkat"]
for animal in animals:
    if animal in animals_away_list:
      animals.remove(animal)
print(animals)
```
Expected Output: ['Tom', 'Bird', 'Dog']


Equivalent script:
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
Actual Output: ['Tom', 'Meerkat', 'Bird', 'Dog']
