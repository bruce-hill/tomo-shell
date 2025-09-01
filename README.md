# Shell

This module defines a `lang` for running shell scripts in
[Tomo](https://tomo.bruce-hill.com):

```
# modules.ini
[shell]
version=1.0
git=https://github.com/bruce-hill/tomo-shell
```

```tomo
use shell

>> $Shell"
    seq 5
    echo DONE
":get_output()
= "1$\n2$\n3$\n4$\n5$\nDONE"
```
