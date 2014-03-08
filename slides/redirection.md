## IO Redirection

```
% command 2>/dev/null
```

```
% command &>/dev/null
```

```
% command >/dev/null 2>&1
```

```
% echo "I'll go to stdout" >&2
```

```
% cat file.txt | grep 'some-pattern'
```

```
% grep 'some-pattern' < file.txt
```

```
% grep 'some-pattern' file.txt
```
