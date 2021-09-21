﻿Regular Recycler is a simple script to scan all of the trash folders it can and delete older files. Set it up with [LazyCron](https://github.com/SurpriseDog/LazyCron) to keep the trash folders clear of older files so they don't take up too much space.

### Usage:

```
  ./RegularRecycler.py --age <file age in days>

```

By default it will simply print each file that would be deleted. To actually delete them run it with the `--destroy` option.