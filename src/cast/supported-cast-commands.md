## Cast Commands Support Matrix

> 🔄 **Last update**: May 2025

| Command                             | Status           | Description                                                                                          |
|:------------------------------------|:-----------------|:-----------------------------------------------------------------------------------------------------|
| cast 4byte-decode                   | ✅ Supported     | Decodes a given 4-byte selector into its associated function signature.                                                                  |
| cast 4byte-event                    | ✅ Supported     | Fetches event signatures from the 4byte.directory by their selector.                                                                     |
| cast abi-decode                     | ✅ Supported     | Decodes ABI-encoded data into a human-readable format.                                                                                   |
| cast abi-encode                     | ✅ Supported     | Encodes data into ABI format for function calls and transactions.                                                                        |
| cast access-list                    | ❌ Not Supported | Generates an access list for a transaction, which can be used to optimize gas usage.                                                     |
| cast address-zero                   | ✅ Supported     | Outputs the zero address (0x0000000000000000000000000000000000000000).                                                                   |
| cast admin                          | ❌ Not Supported | Returns the admin of a specified proxy contract.                                                                                         |
| cast age                            | ✅ Supported     | Calculates the age of a block in seconds.                                                                                                |
| cast balance                        | ✅ Supported     | Retrieves the balance of an address in wei or ether.                                                                                     |
| cast base-fee                       | ✅ Supported     | Fetches the base fee of the latest block, useful for estimating gas costs.                                                               |
| cast bind (DEPRECATED)              | ✅ Supported     | Generates Go bindings for Solidity contracts, similar to forge bind.                                                                     |
| cast block                          | ✅ Supported     | Retrieves detailed information about a specific block on the blockchain.                                                                 |
| cast block-number                   | ✅ Supported     | Returns the current block number of the Ethereum blockchain.                                                                             |
| cast call                           | ✅ Supported     | Executes a read-only (constant) call to a smart contract.                                                                                |
| cast call --create                  | ✅ Supported     | Calls a contract and creates a new contract in the same transaction.                                                                     |
| cast calldata                       | ✅ Supported     | Encodes function call data for a contract, which can be used in transactions.                                                            |
| cast calldata-decode                | ✅ Supported     | Decodes encoded calldata back into its original arguments.                                                                               |
| cast chain                          | ✅ Supported     | Displays name of the current chain.                                                        |
| cast chain-id                       | ✅ Supported     | Returns the chain ID of the Ethereum network, which is used for transaction signing.                                                     |
| cast client                         | ✅ Supported     | Fetches information about the connected Ethereum client, such as its version.                                                            |
| cast code                           | ✅ Supported     | Retrieves the bytecode of a contract deployed at a specific address.                                                                     |
| cast codesize                       | ✅ Supported     | Returns the size of the bytecode at a specific address, in bytes.                                                                        |
| cast completions                    | ✅ Supported     | Generates shell completions for cast, improving command-line usability.                                                                  |
| cast compute-address                | ✅ Supported     | Computes the Ethereum address for a contract deployed by a specific account.                                                             |
| cast concat-hex                     | ✅ Supported     | Concatenates multiple hexadecimal values into a single hex string.                                                                       |
| cast create2                        | ✅ Supported     | Computes the address of a contract deployed using the CREATE2 opcode.                                                                    |
| cast decode-eof                     | ❌ Not Supported | Decodes Ethereum Object Format (EOF) bytecode, used in Ethereum contracts.                                                               |
| cast decode-transaction             | ✅ Supported     | Decodes the data and parameters of a raw transaction.                                                                                    |
| cast disassemble                    | ❌ Not Supported | Disassembles contract bytecode into readable EVM assembly instructions.                                                                  |
| cast estimate                       | ✅ Supported     | Estimates the gas cost of executing a transaction on the blockchain.                                                                     |
| cast estimate --create              | ✅ Supported     | Estimates the gas cost for deploying a contract with a creation transaction.                                                             |
| cast source                         | ❌ Not Supported | Fetches and displays the verified source code of a contract from  a block explorer.                                                              |
| cast find-block                     | ✅ Supported     | Finds a block based on a given timestamp, returning the block number.                                                                    |
| cast format-bytes32-string          | ✅ Supported     | Converts a string into a bytes32 format for Solidity.                                                                                    |
| cast from-bin                       | ✅ Supported     | Decodes binary-encoded data into a human-readable format.                                                                                |
| cast from-fixed-point               | ✅ Supported     | Converts a fixed-point number into a human-readable string.                                                                              |
| cast from-rlp                       | ✅ Supported     | Decodes RLP-encoded data, commonly used in Ethereum transactions.                                                                        |
| cast from-utf8                      | ✅ Supported     | Converts a UTF-8 string to a hex-encoded representation.                                                                                 |
| cast from-wei                       | ✅ Supported     | Converts a value from wei (the smallest unit of ether) to ether.                                                                         |
| cast gas-price                      | ✅ Supported     | Fetches the current gas price on the Ethereum network.                                                                                   |
| cast generate-fig-spec              | ✅ Supported     | Generates a Fig spec for Cast, which can be used for command-line autocomplete functionality.                                            |
| cast hash-message (DEPRECATED)      | ✅ Supported     | Hashes a message using Ethereum's eth_sign method, preparing it for signing.                                                             |
| cast hash-zero                      | ✅ Supported     | Returns the hash of an empty string (0x000...000) using Keccak-256.                                                                      |
| cast implementation                 | ✅ Supported     | Returns the implementation address of a specified proxy contract.                                                                        |
| cast index                          | ❌ Not Supported | Fetches the indexed logs of an event from the blockchain, useful for querying historical data.                                           |
| cast index-erc7201                  | ✅ Supported     | Fetches the logs of an ERC-7201 compliant event from the blockchain                                                                      |
| cast interface                      | ❌ Not Supported | Generates a Solidity interface from a deployed contract’s ABI.                                                                           |
| cast keccak                         | ✅ Supported     | Computes the Keccak-256 hash of the provided input data.                                                                                 |
| cast logs                           | ✅ Supported     | Fetches logs and events from the blockchain, based on specified filters.                                                                 |
| cast lookup-address                 | ✅ Supported     | Fetches the ENS name associated with a given Ethereum address, if any.                                                                   |
| cast max-int                        | ✅ Supported     | Outputs the maximum value for a signed 256-bit integer.                                                                                  |
| cast max-uint                       | ✅ Supported     | Outputs the maximum value for an unsigned 256-bit integer.                                                                               |
| cast min-int                        | ✅ Supported     | Outputs the minimum value for a signed 256-bit integer.                                                                                  |
| cast mktx                           | ✅ Supported     | Creates a transaction object without sending it, useful for offline signing.                                                             |
| cast mktx --create                  | ✅ Supported     | Creates a transaction that deploys a contract, without sending it.                                                                       |
| cast namehash                       | ✅ Supported     | Computes the ENS namehash for a given domain name.                                                                                       |
| cast nonce                          | ✅ Supported     | Retrieves the nonce of an Ethereum address, useful for determining transaction order.                                                    |
| cast parse-bytes32-address          | ✅ Supported     | Parses a bytes32 value into an Ethereum address.                                                                                         |
| cast parse-bytes32-string           | ✅ Supported     | Parses a bytes32 value into a human-readable string.                                                                                     |
| cast pretty-calldata                | ✅ Supported     | Formats calldata in a human-readable manner.                                                                                             |
| cast proof                          | ❌ Not Supported | Retrieves and displays a Merkle proof for a specific storage slot or account.                                                            |
| cast publish                        | ✅ Supported     | Publishes a smart contract's ABI to Etherscan.                                                                                           |
| cast receipt                        | ✅ Supported     | Fetches and displays the receipt of a transaction, including gas used and status.                                                        |
| cast resolve-name                   | ❌ Not Supported    | Resolves an ENS name to its associated Ethereum address.                                                                                 |
| cast rpc                            | ✅ Supported     | Sends a raw JSON-RPC request to an Ethereum node, allowing low-level interaction.                                                        |
| cast run                            | ❌ Not Supported | Runs a script file, such as a .js or .ts file, with access to Cast functions.                                                            |
| cast selectors                      | ❌ Not Supported | Fetches the function selectors for a given contract or ABI.                                                                              |
| cast send                           | ✅ Supported     | Sends a transaction to the blockchain, including smart contract interactions.                                                            |
| cast send --create                  | ✅ Supported     | Sends a transaction that creates a new contract on the blockchain.                                                                       |
| cast shl                            | ✅ Supported     | Performs a bitwise left shift on the provided input.                                                                                     |
| cast shr                            | ✅ Supported     | Performs a bitwise right shift on the provided input.                                                                                    |
| cast sig                            | ✅ Supported     | Outputs the Keccak-256 hash of a function signature.                                                                                     |
| cast sig-event                      | ✅ Supported     | Outputs the Keccak-256 hash of an event signature.                                                                                       |
| cast storage                        | ✅ Supported     | Fetches and displays the raw storage value of a contract at a specific slot.                                                             |
| cast storage-root                   | ❌ Not Supported | Fetch the storage root hash for a given account                                                                                          |
| cast to-ascii                       | ✅ Supported     | Converts a hexadecimal string to an ASCII string.                                                                                        |
| cast to-base                        | ✅ Supported     | Converts a number to a different base (e.g., from decimal to hexadecimal).                                                               |
| cast to-bytes32                     | ✅ Supported     | Converts input data to a bytes32 format.                                                                                                 |
| cast to-check-sum-address           | ✅ Supported     | Converts an Ethereum address to a checksummed format, which includes capital letters for error detection.                                |
| cast to-dec                         | ✅ Supported     | Converts input data to a decimal number.                                                                                                 |
| cast to-fixed-point                 | ✅ Supported     | Converts input data to a fixed-point number representation.                                                                              |
| cast to-hex                         | ✅ Supported     | Converts input data to a hexadecimal format.                                                                                             |
| cast to-hexdata                     | ✅ Supported     | Converts input data to hex-encoded binary data.                                                                                          |
| cast to-int256                      | ✅ Supported     | Converts input data to a signed 256-bit integer.                                                                                         |
| cast to-rlp                         | ✅ Supported     | Encodes input data in Recursive Length Prefix (RLP) format.                                                                              |
| cast to-uint256                     | ✅ Supported     | Converts input data to an unsigned 256-bit integer.                                                                                      |
| cast to-unit                        | ✅ Supported     | Converts ether or wei into different units, like gwei or finney.                                                                         |
| cast to-utf8                        | ✅ Supported     | Converts a hexadecimal string to a UTF-8 encoded string.                                                                                 |
| cast to-wei                         | ✅ Supported     | Converts ether or other units into wei, the smallest unit of ether.                                                                      |
| cast tx                             | ✅ Supported     | Fetches and displays details of a specific Ethereum transaction.                                                                         |
| cast upload-signature               | ✅ Supported     | Uploads a function or event signature to the 4byte.directory.                                                                            |
| cast wallet                         | ✅ Supported     | A suite of wallet-related commands, allowing you to manage Ethereum wallets, create new ones, sign transactions, and more.               |
| cast wallet new                     | ✅ Supported     | Generates a new Ethereum wallet with a private key and address.                                                                          |
| cast wallet new-mnemonic            | ✅ Supported     | Creates a new wallet using a mnemonic phrase, which can be used to recover the wallet later.                                             |
| cast wallet vanity                  | ✅ Supported     | Generates a new wallet with a custom, vanity address (e.g., one that starts with specific characters).                                   |
| cast wallet address                 | ✅ Supported     | Outputs the Ethereum address associated with a given private key.                                                                        |
| cast wallet sign                    | ✅ Supported     | Signs a message or transaction using the private key of a specified wallet.                                                              |
| cast wallet sign-auth               | ✅ Supported     | Signs an authorization message with a private key, often used in authentication workflows.                                               |
| cast wallet verify                  | ✅ Supported     | Verifies a signed message, confirming that it was signed by the holder of the private key associated with a specific address.            |
| cast wallet import                  | ✅ Supported     | Imports an Ethereum wallet using a private key or mnemonic phrase.                                                                       |
| cast wallet list                    | ✅ Supported     | Lists all wallets stored in a specific keystore.                                                                                         |
| cast wallet private-key             | ✅ Supported     | Outputs the private key associated with a given wallet, provided proper authentication.                                                  |           									|
