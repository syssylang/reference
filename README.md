# reference ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/typerust/reference) ![GitHub issues](https://img.shields.io/github/issues/typerust/reference) ![GitHub pull requests](https://img.shields.io/github/issues-pr/typerust/reference)

Every source file is a term. File extension: ```.tr```.

# Terms

## Keywords

### Strictness

#### Strict

#### Permissive

### Uses

### Moves

### Mutability

#### Mut

#### Immut

### Type substructures

#### Affine

#### Linear

#### Relevant

## user-definable

### Functions

### Tuples

### Structs

### Struct instances

### Enums

### Traits

### Impls

### Effects

### Syntax extensions

### Effectors

### Identifiers

### Refinement

### Expressions

## ```base```

### Numbers

* dec: ```42```
* bin: ```0b101010```
* hex: ```0x2A``` (UPPERCASE only)
* float: ```42.0```, ```4.2E+1```

```base``` numerical types (may vary depending on the platform):
* signed 8-bit integer: ```i8``` (```base.i8.i8```)
* unsigned 8-bit integer: ```nn_i8``` (```base.nn_i8.nn_i8```)
* signed 16-bit integer: ```i16``` (```base.i16.i16```)
* unsigned 16-bit integer: ```nn_i16``` (```base.nn_i16.nn_i16```)
* signed 32-bit integer: ```i32``` (```base.i32.i32```)
* unsigned 32-bit integer: ```nn_i32``` (```base.nn_i32.nn_i32```)
* signed 64-bit integer: ```i64``` (```base.i64.i64```)
* unsigned 64-bit integer: ```nn_i64``` (```base.nn_i64.nn_i64```)
* signed 128-bit integer: ```i128``` (```base.i128.i128```)
* unsigned 128-bit integer: ```nn_i128``` (```base.nn_i128.nn_i128```)
* 32-bit float integer: ```f32``` (```base.f32.f32```)
* 64-bit float integer: ```f64``` (```base.f64.f64```)

### Bools
```bool``` (```base.bool.bool```), is enum with 2 variants
* ```true``` (```base.bool.bool.true```)
* ```false``` (```base.bool.bool.false```)

### Chars

```char``` (```base.char.char```) is 32-bit valid utf8 character
* ```'a'```
* ```'\n'```
* ```'\u00E9'``` (hex is UPPERCASE only)

### Strs

```str```s (```base.str.str```) are always valid UTF-8 and are usually seen in its borrowed form, &str
* ```"abc\n"```
