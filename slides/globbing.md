## Globs

```
% ls *.mp4
foo.mp4 bar.mp4
```

```
% for file in *.mp4; do
>   echo "A file! $file"
> done
A file! foo.mp4
A file! bar.mp4
```
