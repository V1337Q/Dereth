# This is a Rust script to Derive an ETH private address, to match a missing private address character to the Public address.

## How to use

1. Clone the repository

2. Insert the Public address in the script

3. Insert the Private address in the script

4.
Run the script 

```bash
cargo run
```

Output:

```
Private Address Found!

Private Address: 0x4f3edf983ac636a65a842ce7c78d9aa706d3b113bce9c46f30d7d21715b23b1d
Public Address: 0x8f3edf983ac636a65a842ce7c78d9aa706d3b113bce9c46f30d7d21715b23b1d
```

## How it works

The script uses the `eth-keystore` crate to derive the private key from the public key.





