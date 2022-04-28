[GitHub Pages](https://jameskabbes.github.io/nanoid)

# nanoid
Simple Python library for generating NanoIDs

# Installation
`pip install kabbes_nanoid`

# Usage
For more in-depth documentation, read the information provided on the Pages. Or better yet, read the code.

## Importing
`import nanoid`

## Get a nanoid string
```
nanoid_string = nanoid.generate()
print (nanoid_string)
```

## Generate a Nanoid object
```
Obj = nanoid.Nanoid()
print (Obj.nanoid)
print (Obj.size)
print (Obj.alphabet)
```

## Set custom generation parameters
```
print (nanoid.generate( size = 10, alphabet = '0123456789ABCDEF' ))
Obj = nanoid.Nanoid( size = 10, alphabet = '0123456789ABCDEF' )
print (Obj.nanoid)
```

# Author
James Kabbes

