# Sequences

A *sequence* is an opaque value representing a finite sequence.  Each element of the sequence is represented by multiple values.

## Predicates

```scheme
(sequence? OBJECT)
```

Returns `#t` if OBJECT is a sequence, and `#f` otherwise.

## Constructors

```scheme
(list->sequence LIST)
```

```scheme
(for-each->sequence FOR-EACH)
```

```scheme
(fold->sequence FOLD)
```

...

## Destructors

```scheme
(sequence-for-each PROC SEQUENCE)
```

```scheme
(sequence-fold PROC NIL SEQUENCE)
```

...

## Converters

```scheme
(sequence->list SEQUENCE)
```

...

## Combiners

```scheme
(sequence-map PROC SEQUENCE)
```

```scheme
(sequence-merge SEQUENCE ...)
```

...
