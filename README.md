# rust-examples
Some examples of snippets I use a lot. Helped me get started and hope it will help others as well.

# Running using `cargo build`

For each folder, cd into the folder and run `cargo build` then `cargo run` and it should work fine.

# Examples

### tcp_server

Starts a local server on port 9123. You can quickly netcat a message to it and it should respond back like this: `echo 1 | netcat localhost 9123`

