<div align="center">

# hey, I'm Moisik 🦀

### bare-metal tinkerer · cryptography enthusiast · perpetual `no_std` learner

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=CE7A5C&center=true&vCenter=true&width=460&lines=cross-compiling+for+Cortex-M33...;reading+register+maps+at+2am...;no+HAL%2C+no+black+boxes...;println!+doesn%27t+exist+here+%F0%9F%98%85" alt="Typing SVG" />

</div>

<br>

## ☕ what I'm brewing

I'm building embedded systems and cryptographic tools in **Rust**, from the metal up. Currently deep in a dissertation project — a bare-metal PN532 NFC driver, written `no_std`, with a **hand-rolled boot runtime** (custom linker script, vector table, and reset handler — no `cortex-m-rt`, no HAL). The goal isn't just "make it work" — it's understanding every layer well enough to know exactly where it could break.

I also maintain a Rust cryptographic library with C FFI, built for FPGA-based embedded targets.

```rust
struct Me {
    languages: Vec<&'static str>,       // Rust, some C when FFI demands it
    currently_reading: &'static str,    // an NXP reference manual, register by register
    coffee_or_tea: Beverage,            // tea, mostly — cozy debugging sessions
    favorite_bug: &'static str,         // the one that taught me the most
}
```

<br>

## 🧵 threads I'm pulling on

- 🔩 **Embedded Rust** — PACs, memory-mapped registers, linker scripts, boot sequences, `unsafe` where it actually earns its keep
- 🔐 **Applied cryptography** — AES, key derivation, secure buffer handling, side-channel awareness
- 🦀 **Rust fundamentals, properly** — ownership, lifetimes, typestate, trait objects — the stuff that makes the compiler your ally instead of your obstacle
- 📡 **NFC / I2C** — protocol framing, bus scanning, talking to real silicon over two wires and a prayer for pull-up resistors

<br>

## 🛠️ tools of the trade

<div align="center">

![Rust](https://img.shields.io/badge/Rust-CE7A5C?style=for-the-badge&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-5C6B73?style=for-the-badge&logo=c&logoColor=white)
![Embedded](https://img.shields.io/badge/Embedded-8A6D5C?style=for-the-badge&logo=arm&logoColor=white)
![Cortex M33](https://img.shields.io/badge/Cortex--M33-A67B5B?style=for-the-badge&logo=nxp&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-6B5B4D?style=for-the-badge&logo=linux&logoColor=white)

</div>

<br>

## 📌 currently pinned in my mind

> a `.bss` section that isn't actually zeroed is just a promise nobody kept

<br>

## 📊 the stats corner

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=transparent&hide_border=true&title_color=CE7A5C&icon_color=CE7A5C&text_color=8A6D5C" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=transparent&hide_border=true&ring=CE7A5C&fire=CE7A5C&currStreakLabel=CE7A5C" height="165"/>

</div>

<br>

<div align="center">

*building things that boot before they run, and run before they trust anyone.*

</div>
