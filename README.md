# hash

> A super lazy file hashing command line tool built on node

## Usage

```
hash [options] <file>
```

## Options

### Algorithm

Use `-a <algorithm>` or `--algorithm <algorithm>`. See `hash --help` for
available algorithms. Defaults to `'md5'`.

```
hash -a md5 <file>
```

### Salt

Use `-s <salt>` or `--salt <salt>`.

```
hash -a md5 -s foobar <file>
```

## License

MIT
