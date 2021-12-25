---
title: "Compile-Time Evaluation, Interpreted Rust, and UB Sanitizing: Talking to Oliver Scherer about Miri"
date: 2019-12-23T18:00:00+00:00
file: https://audio.rustacean-station.org/file/rustacean-station/rustacean-station-e008-miri-oli-obk.mp3
duration: "24:29"
length: "23497525"
reddit: https://www.reddit.com/r/rust/comments/eep97x/compiletime_evaluation_interpreted_rust_and_ub/
---

In the first of our mini-interviews from RustFest 2019, we talk to [Oliver Scherer](https://twitter.com/oli_obk){:target="_blank"} about [Miri](https://github.com/rust-lang/miri){:target="_blank"}, an interpreter for rustc's internal bytecode, its use in `const`-evaluation, and its potential as an external tool for sanitizing `unsafe` code.

<!--
The episode introduction goes here.
The first paragraph should ideally be short, and is used in various
places as a "short description" for the episode. Any subsequent
paragraphs show up as "expanded description".
-->

### Contributing to Rustacean Station

<!-- You can probably leave this as-is -->

Rustacean Station is a community project; get in touch with us if you'd like to be interviewed, propose a topic for an episode, or help create the podcast itself!

 - Twitter: [@rustaceanfm](https://twitter.com/rustaceanfm){:target="_blank"}
 - Discord: [Rustacean Station](https://discord.gg/cHc3Gyc){:target="_blank"}
 - Github: [@rustacean-station](https://github.com/rustacean-station/){:target="_blank"}
 - Email: [hello@rustacean-station.org](mailto:hello@rustacean-station.org){:target="_blank"}

### Timestamps & referenced resources

- [@01:15] - What is `const`-evaluation and what can you do with it?
- [@03:23] - What is Miri and how long has it been in development?
- [@07:05] - What does the future hold for Miri?
- [@07:54] - How long have you been working on rustc and Miri?
- [@12:22] - How much of Miri does rustc use today?
- [@13:33] - How does Miri help people detect undefined behavior in `unsafe` code?
- [@16:46] - How would a user begin using Miri directly to test their `unsafe` code?
- [@19:15] - What happens if you try to `const`-evaluate `unsafe` code?
- [@20:33] - What's next for `const`-evaluation in rustc?
- [@21:58] - Who else is helping to develop Miri?

<!--
In this section, leave timestamped notes of the form:

 - [@HH:MM:SS] - Topic at first timestamp
 - [@HH:MM:SS] - Topic at second timestamp
     - A link to additional material discussed during the preceding topic

-->

### Credits

Intro Theme: [Aerocity](https://twitter.com/AerocityMusic){:target="_blank"}

Audio Editing: alphastrata

Hosting Infrastructure: [Jon Gjengset](https://twitter.com/jonhoo/){:target="_blank"}

Show Notes: [Ben Striegel](https://twitter.com/bstrie){:target="_blank"}

Hosts: [Ben Striegel](https://twitter.com/bstrie){:target="_blank"}
