# python_snippets
## Bits and pieces of code

### Single line print.
```
name = 'Sir/Madam'
language = 'Python'

print(
        r"""What's a line? """
        rf"""I don't know, {name}. """ 
        rf"""Maybe there's something about {language}."""
)

print(
        r"""What's a line?""",
        rf"""I don't know, {name}.""",
        rf"""Maybe there's something about {language}."""
)

print(r"""What's a line? """ rf"""I don't know, {name}. """ rf"""Maybe there's something about {language}.""")
print(r"""What's a line?""", rf"""I don't know, {name}.""", rf"""Maybe there's something about {language}.""")
```
Outputs:
```
What's a line? I don't know, Sir/Madam. Maybe there's something about Python.
What's a line? I don't know, Sir/Madam. Maybe there's something about Python.
What's a line? I don't know, Sir/Madam. Maybe there's something about Python.
What's a line? I don't know, Sir/Madam. Maybe there's something about Python.
```
### Apples are oranges
```
apples, oranges = 'apples', 'oranges'

if apples and oranges:
    print(f'Apples and oranges are {apples and oranges}.')
```
Outputs:
```
Apples and oranges are oranges.
```
