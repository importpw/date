# date

Date processing functions for shell scripts.


## API

### `date_now`

Prints the current time in seconds since the [Unix
epoch](https://en.wikipedia.org/wiki/Unix_time) (1970-01-01 00:00:00 UTC).

```bash
#!/usr/bin/env import
import "date"

date_now
# 1590871495
```
