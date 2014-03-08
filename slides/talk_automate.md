```bash
#!/bin/sh

talks="$HOME/Code/talks"
reveal_version='2.6.1'
reveal_src_url="https://github.com/hakimel/reveal.js/archive/${reveal_version}.tar.gz"

title="$*"
directory="$talks/$(printf "$title" | sed 's/.*/\L&/; s/ \+/_/g')"

curl -L -# "$reveal_src_url" | tar fxz -
mv "reveal.js-$reveal_version" "$directory"

cat > "$directory/index.html" << EOF
<!doctype html>
<html lang="en">
  <!-- ... -->
</html>
EOF
```
