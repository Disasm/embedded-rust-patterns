# Embedded Rust Patterns

> A list of frequently used patterns for embedded Rust development

## General
* `PhantomData<*const ()>`
* `#![deny(warnings)]`: [known anti-pattern](https://github.com/rust-unofficial/patterns/blob/master/anti_patterns/deny-warnings.md).

## HAL and drivers
* Extension traits
* "Impossible error" type
* Pin traits
* macro-based code generation
* GPIO pin downgrade
* splitting UART peripheral for Tx+Rx
* pin configuration inside the peripheral vs outside
