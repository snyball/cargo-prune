`cargo-prune`
=============

A small shell utility to run `cargo clean` on projects older than some date.
Specifically, based on the mtime of the `target` directory.

```bash
cargo-prune '2 weeks ago' my-projects/
```

Defaults to '1 week ago' in the current directory.
