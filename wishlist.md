List of things I would like to change in Rust's `std`:
- remove all deprecated functions (obviously)
- `Vec::{remove,swap_remove}` should return `Option<T>` instead of `T`
- Make it impossible to implement `Into` and `TryInto` e.g with a sealed Trait
- Remove FromStr and use `TryFrom<&str>` as a bound in `str::parse` instead
- Change associated types to GATs where appropriate (e.g. Iterator, Index)
