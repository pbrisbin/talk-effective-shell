## Multi-line

```
% printf "%s\n" "foo" "bar" |\
>   grep "o" | sed 's/f/m/'
moo
```
