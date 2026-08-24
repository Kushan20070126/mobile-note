# Conditions and loop

## When expressions and statements

- When Statement to replace switch


Syntax : 

```
when(<variable/expressions>){

<value> -> { <Statement> extented when varibale equals value}
<value> -> { <Statement> extented when varibale equals value}

else -> { <Statement> extented when varibale not equals value}

```


- when Statement replacing if else-if

Syntax:

```
when{
    <condition> -> {<Statement> extented when condition is true}
    <condition> -> {<Statement> extented when condition is true}
    else -> {<Statement> extented when condition is not true}

}

```

---

# Loop

## Range 

syntax : 

```
(counter in 1..10)
```


## Incremental Loop

syntax : 

```
for(<variable> in <lower-bound>..<upper-bound> step <int>){
    //statement
}

```

## Decremental Loop

Syntax : 

```
for(<variable> in <upperbound> down to <Lowerbound> step <int>){
    //statement

}

```
---


