## CS-511 Notes
---

### October 25, 2021

## Introduction to Erlang

Run the interpreter with `erl`


Cons operator: `|`
```
[3 | [1,2,3,4]]
[3,1,2,3,4]

```

List comprehension: `||`

```
[X * X || x<- lists:seq(1,100)].
[1,4,9,16,25,36,49...]

```

Pattern matching: `=`

```
$> X = 5.
$> X.
$> 5
$> X = 4.
$> No match of right hand side
```



## NO assignments in Erlang.

