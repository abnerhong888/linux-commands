## linux-commands

# grep
```bash
  grep -Znr . -e <pattern>
  grep -Znr --include=\*.{<ext1, ext2>} . -e <pattern>
```
# tar
```bash
  # use gzip compress
  tar -cvzf <name>.tar.gz <folder or file>

  # use tar compress
  tar -cvf <name>.tar <folder or file>

  # extract file
  tar -xvf <file name> -C <directory>
```

# code size
```bash
  size <.o, .so ...>
```

# obj dump
```bash
  objdump -Slz a.out
```


# profiling
```bash
  valgrind ...
  perf ...
```
