# asak

A cross-platform audio recording/playback CLI tool with TUI, written in Rust. The goal is to be an audio Swiss Army Knife (asak), like SoX but more interative and fun.

![asak](https://github.com/chaosprint/asak/assets/35621141/06ca6aed-939d-4bcb-b602-0d54b92626c3)

## install

> You need to have `cargo` installed, see [here](https://doc.rust-lang.org/cargo/getting-started/installation.html).

### step 1

```sh
cargo install asak
```

### step 2

```sh
asak --help
```

## usage

### record

```sh
asak rec hello
```

If no output name is provided, it will default to UTC format such as `2024-04-14T09:17:40Z.wav`.

### playback

```sh
asak play hello.wav
```

> If no input name is provided, it will search current directory for `.wav` files and open an interactive menu.

## roadmap?

- [x] record audio
- [x] basic audio playback
- [ ] rec device, dur, sr, ch, fmt
- [ ] play device, dur, sr, ch, fmt
- [ ] playback live pos control
- [ ] live amp + fx (reverb, delay, etc)
- [ ] passthru + live fx

## contribution

Just open an issue or PR, I'm happy to discuss and collaborate.
