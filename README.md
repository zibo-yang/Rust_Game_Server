# Rust_Game_Server
The game server is part of our software engineer project. 

## Install
Please install the [rust-lang](https://www.rust-lang.org/tools/install) and [telnet](https://www.layerstack.com/resources/tutorials/Installing-telnet-on-Linux-and-Windows-Cloud-Servers) first

## Usage
Use the following commands to initialize the rust game server
```bash
cd server
cargo run
```
After the server start on, open the telnet and set the local echo to make the feedback visible like:
```bash
telnet 127.0.0.1 80
```
After you see the keyword like connection on the server side, then you can begin testing the server by typing and sending the message like "Q12.map:1,2,3,4" and have a look at the corresponding feedback you receive from the rust server. All the efficient messages have been clarified in the specification below.
## Specification
Please have a look at specification.pdf.

## License
Licensed under [MIT License](LICENSE)
