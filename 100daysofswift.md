# 100 Days of Swift Cheatsheet

## Simple Data Types

### Variables

```swift
var str = "Hello, playground"
```
### Constants

```swift
let taylor = "swift"
```

### Explicit Types

```swift
let album: String = "Reputation"
let year: Int = 1989
var height: Double = 1.78
var taylorRocks: Bool = true
```

## Strings

### String Interpolation

```swift
var score = 85
var str = "Your score was \(score)"
```

### Multi-line Strings for Display

```swift
var str1 = """
This goes
over multiple
lines
"""
```

### Multi-line Strings for Code Formatting

```swift
var str2 = """
This goes \
over multiple \
lines
"""
```

## Complex Data Types

### Arrays

1. **Dynamic Size**: Arrays can grow or shrink in size.
2. **Type-Safe**: All elements must be of the same type.
3. **Mutable or Immutable**: Use `var` for mutable arrays and `let` for immutable arrays.
4. **Zero-Based Indexing**: Elements are accessed using zero-based indices.
5. **Common Collection Type**: Widely used for ordered collections of items.

```swift
let john = "John Lennon"
let paul = "Paul McCartney"
let george = "George Harrison"
let ringo = "Ringo Starr"

let beatles = [john, paul, george, ringo]
```

### Sets

1. **Unique Elements**: Sets store unique values with no duplicates.
2. **Unordered**: Sets do not maintain any particular order.
3. **Type-Safe**: All elements must be of the same type.
4. **Fast Lookups**: Optimized for fast membership checks.
5. **Mutable or Immutable**: Use `var` for mutable sets and `let` for immutable sets.

```swift
let colors = Set(["red", "green", "blue"])
```

### Tuples

1. **Fixed Size**: Tuples have a fixed size defined at creation.
2. **Type-Safe**: Each element can be of a different type.
3. **Mutable Elements**: Elements can be modified if the tuple is a `var`.
4. **No Addition/Removal**: Cannot add or remove elements.
5. **Ad-Hoc Grouping**: Useful for temporarily grouping values and returning multiple values from functions.

```swift
var name = (first: "Taylor", last: "Swift")
name.0
name.first
```

### Dictionaries

1. **Key-Value Pairs**: Stores data as key-value pairs.
2. **Unique Keys**: Each key must be unique within the dictionary.
3. **Unordered**: Does not maintain any particular order of elements.
4. **Type-Safe**: Keys and values must be of specified types.
5. **Mutable or Immutable**: Use `var` for mutable dictionaries and `let` for immutable dictionaries.

```swift
let heights = [
    "Taylor Swift": 1.78,
    "Ed Sheeran": 1.73
]

heights["Taylor Swift"]
```

#### Default Value

```swift
heights["Yao Ming", default: "Unknown"]
```

### Creating Empty Collections (Dictionaries, Arrays & Sets)

```swift
// Empty Dictionary
var teams = [String: String]() // or
var scores = Dictionary<String, Int>()
// Empty Array
var results = [Int]() // or
var results = Array<Int>()
// Empty Sets
var words = Set<String>()
var numbers = Set<Int>()
```

### Enumerations

