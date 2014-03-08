```no-highlight
% echo "A-really bad.title" | sed 's/[ -.]\+/_/g; s/.*/\L&/'
"a_really_bad_title"
```

```no-highlight
% for file in *; do
>   fixed="$(echo "${file%.*}" | sed 's/[ -.]\+/_/g; s/.*/\L&/')"
>   ext="${file##*.}"
>   echo "$fixed ($ext)"
> done
hot_rod (mp4)
the_big_lebowski (m4v)
in_bruges (iso)
brick (mp4)
```
