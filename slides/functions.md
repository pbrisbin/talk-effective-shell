## Functions

```no-highlight
% fix_file() {
>   local file="$1" fixed_file
>
>   # lower case letters, remove spaces etc
>   fixed_file="$( ... )"
>
>   echo "$fixed_file"
> }
```

```no-highlight
% for file in *; do
>   fixed="$(fix_file "$file")
>
>   mv "$file" "$fixed"
> done
```
