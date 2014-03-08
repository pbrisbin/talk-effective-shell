## Pipeline

```
% grep -F 'error' log.txt | cut -d ' ' -f 3 | sort | uniq -c | sort -rn
    12 2013-03-05
     7 2013-03-08
     6 2013-03-04
     4 2013-03-06
     3 2013-03-02
     1 2013-03-09
```

Build these up incrementally
