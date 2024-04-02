`cargo-prune`
=============

A small shell utility to run `cargo clean` on projects older than some date.

```bash
$ cargo-prune '2 weeks ago' my-projects/
```

Defaults to '1 week ago' in the current directory.
