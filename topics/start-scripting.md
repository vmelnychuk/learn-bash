## script file basics
- start file with `#!` (pound sign and exclamation mark), magic number `0x2300x21`
- add path to your shell e.g. `/bin/bash` or `/usr/bin/env bash` [1](#1)
- example:
```shell
./create-dictionary
creating dictionary...
/bin/bash ./create-dictionary
creating dictionary...
```
- result of `cat create-dictionary`:
```bash
#!/bin/bash

echo creating dictionary...
```

##### 1
What to use `/bin/bash` or `/usr/bin/env bash`. Some times `/usr` is not mounted and you can use only `/bin/bash`.
