```no-highlight
% for file in *; do
>   fixed="$(echo "${file%.*}" | sed 's/[ -.]\+/_/g; s/.*/\L&/')"
>   ext="${file##*.}"
>   mv -v "$file" "$fixed.$ext"
> done
’hot.rod.mp4’ -> ’hot_rod.mp4’
’The Big Lebowski.m4v’ -> ’the_big_lebowski.m4v’
’in-Bruges.iso’ -> ’in_bruges.iso’
’bRick.mp4’ -> ’brick.mp4’
```
