## icon reference

💭 thinking about

🔎 notice

⚠️ watch out

🐯 YOU ARE HERE

> action item

🧋 [ requested from ] `info needed`

---

*note* `Win+.` to access emoji menu

---

## variable syntax

all defined variables will follow the below convention:
- functions:
    - `fxn` :   user-defined function
    - `plt` :   plotting function (returns a plot)
    - `hlpr`:   helper function, usually for plotting, intended for use in other functions or as part of plot creation
- datasets
    - `info`:   informational variables, often dataframes, series, lists, or other such collections, output shows useful data
    - `ref` :   reference variables, intended for use in calculations or other internal applications
    - `data`:   holds imported and/or processed data
- `_HB_`:   follows an above prefix, used exclusively/ primarily for the 1051HB dataset
- mapping
    - `map` :   for files and vars that go into making a map
    - `_XX_`:   state abbr. (e.g., CO) for the map

> [!tip] callout test
>
> test

<div class="alert alert-info">Info message</div>

[Functions](#functions "go to function")

==test==  
new line?  
also now??

:smile:

## Python syntax (PEP-8)

line limit: 72 for comments, 79 otherwise

can use the following as a reference guide

#----------------------------------------------------------------------#

> TBH I don't think this matters all that much  
> just good to remember to not let things get too long

## Cell layout

```py
#___ this is a short title of what the cell does ___#

# optional description & notes can go here
# can also write general NOTE's and TODO's etc. up here
# don't need to do this top section for a function

print('Hello world')

#___ use this for sections in a longer cell if needed ___#

for i in range(5):
    # simple comments (match tab) for clarity
    for j in range (3):
        # used to make sure following code flow is understood
        # can use multiple lines if needed
        print(f'= {i+j}')

# NOTE: use codetags as needed with date <2026-05-14>

# NOTE: if multiple lines
# put end tag at bottom
# <2026-05-14>
```