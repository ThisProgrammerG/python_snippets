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
