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

```swift
let john = "John Lennon"
let paul = "Paul McCartney"
let george = "George Harrison"
let ringo = "Ringo Starr"

let beatles = [john, paul, george, ringo]
```

### Sets

```swift
let colors = Set(["red", "green", "blue"])
```

### Tuples

```swift
var name = (first: "Taylor", last: "Swift")
name.0
name.first
```