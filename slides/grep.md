## Grep

```
% grep line file.txt
one line
two line
three line
```

```
% cat file.txt other-file.txt | grep five
five and six
```

```
% grep -q line file.txt; echo $?
0
```

```
% grep -q "something else" file.txt; echo $?
1
```
