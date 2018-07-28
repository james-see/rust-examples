# rust-examples
Some examples of snippets I use a lot. Helped me get started and hope it will help others as well.

## Installing Rust

1. Run `curl https://sh.rustup.rs -sSf | sh`

2. then make sure Cargo is in your path by adding this to your profile: `export PATH="$HOME/.cargo/bin:$PATH"`. I use [oh-my-zsh](https://ohmyz.sh) so I just do `nano ~/.zshrc` then add that line to the bottom via CTRL + W and then CTRL + V to get to the bottom quickly, or you could just echo it to .zshrc via `echo 'export PATH="$HOME/.cargo/bin:$PATH"' >> ~.zshrc`.


## Running using `cargo build`

For each folder, cd into the folder and run `cargo build` then `cargo run` and it should work fine.

## Examples

### tcp_server

Starts a local server on port 9123. 

You can quickly netcat a message to it and it should respond back like this: 

`echo 1 | netcat localhost 9123`

### more coming soon

