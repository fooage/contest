This is the usual `C++` and `Go` code templates, which adds the universal header file `<bits/stdc++.h>` and the namespace `std`. There are two parts left to fill in the code separately. `Go` template is mainly used for leetcode, generally not used for ACM competitions.

## Installation

The installation is very simple, first make sure to compile the environment and then download it for use.

```bash
git clone https://github.com/fooage/contest.git
```

## Content

### Global definition

- `mod`

This is a commonly used modulo variable, and the variable default value is `1e9 + 7`.

- `ll`

As a shorthand for the `long long` data type.

- `ull`

In the same way, it is an abbreviation of `unsigned long long` to speed up encoding.

### Detail optimization

- Optimized the speed of input and output

- Use the `sync_with_stdio` should avoid mixing `prinf` and `cout`, same for `scanf` and `cin`

### Algorithm template

Ready to add some basic algorithm templates, such as gcd, fast power and verification prime numbers, etc. These templates will be presented on my blog <https://fooage.github.io/fooage/>!
