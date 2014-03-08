## Sed

```
% sed 's/line/word/' file.txt
one word
two word
three word
four
```

```
% sed '/\(.*\) \(.*\)/!d; s//\1-"\2"/'
one-"line"
two-"line"
three-"line"
```
