## Return and print are different things

A lot of people get this wrong because they learn to code using a REPL. Java folks are less likely to fall into this trap.

Here are some basic code examples. It is in Python but easy to translate to other languages.

```python
def foo():
    print("hi")

x = foo()
print(f"x = {x}")
```

Many think that the code will print `x = hi`. It does not.

## Multiple different return statements inside a single function

For example:

```python
def foo(colour):
    if colour == "blue":
        return 1
    return 2
```

## Multiple function calls

```python
x = foo("blue")
x = foo("red")
print(f"x = {x}")
```

Many people think that the final print statement gets executed multiple times but it does not.

## Return statements inside for loops

```python
def foo():
    for i in range(10):
        return i

x = foo()
print(f"x = {x}")
```

## Function arguments/parameters

```python
def foo(*args):
    return args

x = foo()
print(f"x = {x}")
```

Many people think that the above will print `x = None`. It will not.

## JavaScript specific concepts

### Hoisting

```javascript
foo();

function foo() {
  console.log("hello");
}
```

Many people assume that the code above will raise an error. It does not.