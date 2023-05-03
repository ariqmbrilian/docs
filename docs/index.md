# Homepage

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code Annotation Examples

### Codeblocks

Some `code` goes here

### Plain codeblock
A plain codeblock:

```
def myfunc():
    pass
```

#### Code for spesific language

```py
import tensorflow as tf
def myfunc():
```

#### With a title
```py title="file.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items [j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### With line numbers
```py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items [j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### Highlighting lines
```py hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items [j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```