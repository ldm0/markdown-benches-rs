# Rust markdown parsers benchmarks

Compares [pulldown_cmark](https://github.com/raphlinus/pulldown-cmark) and [comrak](https://github.com/kivikakk/comrak).

My i7-7700HQ:

```bash
test bench_comrak_article              ... bench:     408,541 ns/iter (+/- 26,185)
test bench_comrak_awesome_rust         ... bench:   9,678,920 ns/iter (+/- 2,974,833)
test bench_pulldown_cmark_article      ... bench:      60,145 ns/iter (+/- 3,372)
test bench_pulldown_cmark_awesome_rust ... bench:     842,667 ns/iter (+/- 276,185)
```

It only has 2 samples right now a medium length article and the readme of 
[awesome-rust](https://github.com/rust-unofficial/awesome-rust) which is pretty long.
