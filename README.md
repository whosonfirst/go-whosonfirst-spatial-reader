# go-whosonfirst-spatial-reader

## Important

This package is deprecated. Since the `go-whosonfirst-spatial/database.SpatialDatabase` interface implements the `reader.Reader` interface it is no longer relevant.

## Interfaces

This package implements the following [go-whosonfirst-spatial](#) interfaces.

### spatial.PropertiesReader

```
import (
	"github.com/whosonfirst/go-whosonfirst-spatial/properties"
	_ "github.com/whosonfirst/go-whosonfirst-spatial-reader"       
)

pr, err := properties.NewPropertiesReader(ctx, "whosonfirst://?reader={READER_uri}&cache={CACHE_URI}")
```

## See also

* https://github.com/whosonfirst/go-whosonfirst-spatial
* https://github.com/whosonfirst/go-reader
* https://github.com/whosonfirst/go-cache
