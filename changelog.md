# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0] - 2025-07-29

### Features

- Implemented additional macros and type aliases:
  - `pb` for `push_back`
  - `eb` for `emplace_back`
  - `mp` for `make_pair`
  - `INF` for a large integer constant
  - `LINF` for a large long long constant
  - `str` for `string`
  - `vll` for `vector<long long>`
  - `vb` for `vector<bool>`
  - `pii` for `pair<int, int>`
  - `vpii` for `vector<pair<int, int>>`
  - `strv` for `string_view`
- Added pragma directives for optimization:
  - `#pragma GCC optimize("O3,unroll-loops")`
  - `#pragma GCC target("avx2,bmi,bmi2,lzcnt,popcnt")`

### Adjustments

- Adjusted solution block to be more concise and efficient.

## [1.0.0] - 2025-07-25

### Features

- Initial release of the core C++ template.
- Basic "New Problem" command for the VS Code extension.