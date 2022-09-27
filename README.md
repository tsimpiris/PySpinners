# PySpinners

## CLI Progress Spinner collection

PySpinners is a collection of (30) progress spinners for CLI applications.

### Version
0.0.1

### Installation
```sh
pip install pyspinners
```

### Usage
```sh
# Create new spinner instance
spinner1 = NewSpinner()

# Any list or any other iterable can be used
lst = [1, 2, 3, 4, 5]

for i, item in enumerate(lst):
    ...do stuff...
    spinner1.spin(i+1, len(lst))
    # Call the .spin() function and give as parameters the iteration number and the length of the iterable.
```

### License

MIT