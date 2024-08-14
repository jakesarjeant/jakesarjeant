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
    .editor("neovim") // VSCode sux <3
    .os("NixOS") // I use nix btw
    .browser("Firefox") // Death to Chromium!
    .search("DuckDuckGo")
    .add_lang("Rust")
    .add_lang("TypeScript")
    .js_framework("React")
    .dark_mode(true)
    .build().unwrap();

  // Pro Tip: Seriously one of the best value for money budget guitars out there
  let guitar = Guitar::builder()
    .manufacturer("Yamaha")
    .name("Pacifica")
    .model("112VMX YNS RL")
    .color("Satin")
    .pickups(vec![Pickup::Humbucker, Pickup::Single, Pickup::Single])
    .build().unwrap();
    
  Person::builder()
    .name("Jake")
    .add_hobby(guitar.into_hobby())
    .add_hobby(programming.into_hobby())
    .email("jake@sarjeant.me".parse())
    .build().unwrap()
};
```
