 <h1 align="center">N O R S E <img align = "top" src="logo/ferris_norse.png" width="32"/></h1>
<p align="center">
    <a href="https://github.com/norse-rs">
       <img src="https://img.shields.io/badge/project-norse-9cf.svg?style=flat-square" alt="NORSE">
    </a>
    <a href="LICENSE-MIT">
      <img src="https://img.shields.io/badge/license-MIT-green.svg?style=flat-square" alt="License - MIT">
    </a>
    <a href="LICENSE-APACHE">
      <img src="https://img.shields.io/badge/license-APACHE2-green.svg?style=flat-square" alt="License - Apache2">
  </a>
</p>

`norse` aims at providing building blocks for parallel systems focusing on computer graphics.

## Platform Target

These are the usual hardware requirements, but not necessarily for all crates.
Typically, explicitly noted if a special ISA is required.

- Instruction set: AVX+
- Vulkan 1.1+
- Rust 2018


## Low Level

- [`billow`](https://github.com/norse-rs/norse-billow) cache-friendly memory block suballocations
- [`physical-device`](https://github.com/norse-rs/norse-physical-device) query CPU hardware information
- [`ash-window`](https://github.com/norse-rs/ash-window) surface creation interop for `ash` from window handles

## Logo

Ferris (norse) emoji based on the Ferris emoji made by Dzuk (noct.zone) (CC BY-NC-SA 4.0)
See `logo/license.txt` for more details.
