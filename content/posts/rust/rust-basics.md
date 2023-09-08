---
title: "[Rust] Rust Basics"
description: "About the flame inside my heart"
date: 2023-09-08T11:00:00+09:00
draft: false
toc: true
tldr: "I hope my flame is eternal, to persevere through longings and hardships."
tags: ["rust", "programming"]
---

## C1. Getting Started

### 1.1. Hello, world!

Writing code in **rust** and compiling with **bash** (WSL env)

```rust
// filename: main.rs
// `!` is an indication of macro
// entry point of Rust code is `main`, akin to c-type langs

fn main(){
    println!("Hello, world!");
}
```

```bash
$ rustc main.rs
$ ./main.rs
```