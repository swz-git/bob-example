# Bob examples repo

This is a repo that contains examples of how you can use bob to build bots. It also
contains a bob.toml in the root of the repo which builds all of the examples
as one example botpack.

## Building

1. Install [bob](https://github.com/swz-git/bob) and [Docker](https://www.docker.com/).
1. Ensure Docker is running.
1. Clone this repo: `git clone https://github.com/swz-git/bob-examples`
1. Change directory into the repo (or one of the bot subfolders): `cd bob-examples`
1. Build! `bob build bob.toml`

## Examples/instructions per language

The bots in this repo are examples of `bob.toml` configurations for various languages. Find the example (and instructions) for a particular language below:

- **Python (Hardcoded):** The `RLBot-Beast` submodule, instructions at [RLBot/python-example](https://github.com/RLBot/python-example?tab=readme-ov-file#configuring-for-the-v5-botpack).
- **Python (ML):** The `Elementv5` submodule, instructions in README.
- **Rust:** The `rust_example` folder, the `bob.toml` is intuitive.
- **C#:** The `csharp-example` submodule, instructions in README.
- **C++ (GigaLearn):** No example, but template and instructions in https://github.com/SubparN0va/GGLBot/tree/bob (bob branch).

For more advanced setups, a custom dockerfile might be needed. In that case, refer to the `prebuilt_binary` folder where a pre-built binary is added. Note however, that binaries are not accepted in the botpack since it defeats the purpose of bob.
