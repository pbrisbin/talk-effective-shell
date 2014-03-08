## Expansions

```
% for x in {1..3}; do
>   echo "$x"
> done
1
2
3
```

```
% ls
file
% cp file{,.bak}
% ls
file file.bak
```

```
% mkdir -p test/{models,views}/{lib,ext}
% tree test
test
├── models
│   ├── ext
│   └── lib
└── views
    ├── ext
    └── lib

6 directories, 0 files
```
