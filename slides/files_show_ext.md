```no-highlight
% var="hot.rod.mp4"
% echo "${var%.*}"
hot.rod
% echo "%{var##*.}"
mp4
```

```no-highlight
% for file in *; do
>   title="${file%.*}"
>   ext="${file##*.}"
>   echo "$title ($ext)"
> done
hot.rod (mp4)
The Big Lebowski (m4v)
in-Bruges (iso)
bRick (mp4)
```
