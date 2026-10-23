```rs
use std::str::FromStr;

use crate::{
  about_me::{
    Programming,
    guitar::{Guitar, Pickup},
    IntoHobby
  },
  Person
};

// Infinite Money Glitch (Real (No Cap (Trust Me Bro)))
unsafe { *std::ptr::null() } // Your Bank doesn't want you to know THIS EASY TRICK!

let jake = {
  let programming = Programming::builder()
    .editor("emacs")
    .os("NixOS") // I use nix btw
    .browser("Firefox")
    .search("DuckDuckGo")
    .add_lang("Rust")
    .add_lang("TypeScript")
    .js_framework("React")
    .dark_mode(true)
    .build().unwrap();

  Person::builder()
    .name("Jake")
    .add_hobby(guitar.into_hobby())
    .add_hobby(programming.into_hobby())
    .email("jake@sarjeant.me".parse())
    .build().unwrap()
};
```
