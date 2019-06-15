# Embedded Rust Patterns

> A list of frequently used patterns for embedded Rust development

## General
* `PhantomData<*const ()>`
* `#![deny(warnings)]`

## HAL and drivers
* Extension traits
* "Impossible error" type
* Pin traits
* macro-based code generation
* GPIO pin downgrade
* splitting UART peripheral for Tx+Rx
* pin configuration inside the peripheral vs outside
