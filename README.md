# reference ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/syssylang/reference) ![GitHub issues](https://img.shields.io/github/issues/syssylang/reference) ![GitHub pull requests](https://img.shields.io/github/issues-pr/syssylang/reference)

Every source file is a value. File extension: ```.sy```.

# Terms

## Keywords

### Uses

### Mutability

#### Mut

#### Immut

### Type substructures

#### Affine

#### Linear

#### Relevant

### Refines

## user-definable

### Functions

### Tuples

### Structs

### Enums

### Variants

### Identifiers

### Expressions

## Literals

### Numbers

* dec: ```42```
* bin: ```0b101010```
* hex: ```0x2A``` (UPPERCASE only)
* float: ```42.0```

### Bools
```bool``` (```base.bool.bool```), is enum with 2 variants
* ```true``` (```base.bool.bool.true```)
* ```false``` (```base.bool.bool.false```)

### Chars

may only be a valid utf8 character: ```'a'```, ```'\n'```, ```'\u00E9'``` (hex is UPPERCASE only)

### Strings

Strings are always valid UTF-8 and are usually seen in its borrowed form
* ```"abc\n"```
