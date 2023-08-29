# v0.3.0 (2023-08-29)
- Handle directories.
- Fix defect in header type declaration.
- Fix defect handling octal numbers with historical space padding.
- Add support for long name (name + prefix) support.
- Add header iterator.
- Internal test improvements.

# v0.2.0 (2023-04-11)
- MSRV is 1.60.0
- bitflags bump: 1.x -> 2.x
- few internal code improvements (less possible panics)
- `Mode::to_flags` now returns a Result
- Feature `all` was removed. Use `alloc` instead.
