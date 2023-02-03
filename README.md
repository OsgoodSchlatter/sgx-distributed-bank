# Distributed bank with SGX Enclave protection

## How to use

- `git clone <repo>`
- `cd sgx-distributed-bank `
- `make `
- may have to source this: `path to /sgxsdk_driver/sgxsdk/environment`. You can use `locate /sgxsdk_driver/sgxsdk`
- `./bank_server_sgx <capacity of bank>`
- `./build/bank_client <nbr of accounts to create>`
