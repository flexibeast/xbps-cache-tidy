# Summary

`xbps-cache-tidy` can be used to remove packages from the XBPS cache that are no
longer required:

```
# ./xbps-cache-tidy --keep 3 --verbose
```

The value for `keep` specifies how many versions to retain.
