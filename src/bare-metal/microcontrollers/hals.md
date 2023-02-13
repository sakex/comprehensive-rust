# HAL crates

[HAL crates](https://github.com/rust-embedded/awesome-embedded-rust#hal-implementation-crates) for
many microcontrollers provide wrappers around various peripherals. These generally implement traits
from [`embedded-hal`](https://crates.io/crates/embedded-hal).

```rust,editable,compile_fail
{{#include examples/src/bin/hal.rs:Example}}
```

<details>

 * `split(...)` enables the GPIO port and returns a struct of its pins.

</details>