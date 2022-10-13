# axioma

An advanced scientific calculator working with text inputs.

[Documentation](https://github.com/david072/axioma/wiki)

![Image](/media/thumbnail.png)

## Downloading

- Desktop Versions with installers available in the [Releases tab](https://github.com/david072/axioma/releases)
- Web:
    - [Stable version](https://david072.github.io/axioma)
    - [Experimental version](https://david072.github.io/axioma/experimental) (might be buggy / unstable)

## Building

Building this project requires that [Rust](https://www.rust-lang.org/) is installed.

1. Clone the project with `git clone https://github.com/david072/axioma`
2. `cd axioma`
3. Run the CLI version with `cargo run -p cli`, the GUI version with `cargo run -p gui`

For the Discord Bot:

1. Create the file `.env` in the top level, and put `DISCORD_TOKEN=<your-bot-token>` into the
   file
2. Run `cargo run -p discord`

To pass arguments to the CLI, use `cargo run -p cli -- <args>`

## Contributing

You can contribute either by using the application and reporting issues and submitting feature requests,
or by forking the project and working on it yourself.
