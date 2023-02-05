# Distributed bank with SGX Enclave protection

## How to use

- `git clone <repo>`
- `cd sgx-distributed-bank `
- `make `
- may have to source this: `path to /sgxsdk_driver/sgxsdk/environment`. You can use `locate /sgxsdk_driver/sgxsdk`
- `./bank_server_sgx <capacity of bank>`
- in another terminal, run `./build/bank_client <nbr of accounts to create>`

## Disclaimer

- doesnt verify ACID properties (yet)

## Credits and code used in this repo

We used this code to get started with the enclave
https://github.com/digawp/hello-enclave

## Authors

Made by joshuarandria and I as part of school project.
