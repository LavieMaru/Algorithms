**Level 6** <br>

Create a function called reverse() that takes in a set of key-value pairs (object in Javascript, hash in Ruby, dictionary in Python, etc.) as the input and returns an object with the same keys and values inverted. If multiple keys have the same value, it should assign of array of keys.

Example:
inputObject: {'a':1, 'b':2}

`reverse(inputObject)` should return {1:'b', 2:'c'}

inputObject2 = {
    "a": "1",
    "b": "2",
    "c": "1",
    "d": "3"
}

`reverse(inputObject2)` should return {
    "1": ["a", "c"],
    "2": ["b"]
    "3": ["d"]
}

Submitted by [KamillaKhabibrakhmanova](https://github.com/KamillaKhabibrakhmanova)
