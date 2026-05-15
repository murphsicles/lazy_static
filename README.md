# @std/lazy_static — Lazy Statics for Zeta

Auto-converted from [lazy_static](https://crates.io/crates/lazy_static) v1.5.0 via Dark Factory.

```zeta
lazy_static! {
    static ref HASHMAP: HashMap<i64, &'static str> = {
        let mut m = HashMap::new();
        m.insert(0, "foo");
        m
    };
}
```

## Stats: 3 source files, 87 lines, 0 unsupported
