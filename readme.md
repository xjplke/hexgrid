# Hexgrid

This is a GO (Golang) library used to handle regular hexagons.
It's based on the algorithms described at http://www.redblobgames.com/grids/hexagons/implementation.html

## Installation

    go get github.com/pmcxs/hexgrid

## Usage
#### Importing

```go
import "github.com/jonas-p/go-shp"
```

### Examples

#### Creating an hexagon

```go
hexagon := hexgrid.NewHexgrid(10)
```


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## History

0.1. First version

## Credits

* Pedro Sousa
* Red Blob Games (http://www.redblobgames.com/grids/hexagons/implementation.html)

## License

MIT