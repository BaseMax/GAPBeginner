# GAP Beginner

A repository to introduce GAP system for beginners.

## Variable

```
universe := 6*7;
m:=[[1,2,3],[4,5,6],[7,8,9]];
```

##  `ColorPrompt()`

```
ColorPrompt(true);
```

## `LogTo()`

```
LogTo("gap-intro.log");
```

## `Display()`

```
Display(m);
```

## `Factorial()`

```
> Factorial(100);
93326215443944152681699238856266700490715968264381621468\
59296389521759999322991560894146397615651828625369792082\
7223758251185210916864000000000000000000000000
```

## `Determinant()`

```
> Determinant(m);
0
```

## `Factors()`

```
> Factors(2^64-1);
[ 3, 5, 17, 257, 641, 65537, 6700417 ]
```

## `Filtered()`

```
> Filtered( [2,9,6,3,4,5], IsEvenInt);
[ 2, 6, 4 ]
```

## `Fibonacci()`

```
> Fibonacci(100);
354224848179261915075
```
