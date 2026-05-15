# @std/lazy_static — Lazy Statics for Zeta

Auto-converted from [lazy_static](https://crates.io/crates/lazy_static) v1.5.0 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features
- **lazy_static!** — declarative lazy-initialized static variables
- **Thread-safe** — initialized once, safe to access across threads
- **Panic-safe** — on panic during init, subsequent access will retry

## Usage
```zeta
use @std/lazy_static::lazy_static;

lazy_static! {
    static ref HASHMAP: HashMap<i64, &'static str> = {
        let mut m = HashMap::new();
        m.insert(0, "foo");
        m
    };
}
```

## Stats: 3 source files, 87 lines, 0 unsupported items

## License
MIT