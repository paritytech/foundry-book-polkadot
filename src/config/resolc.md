## Resolc support

Foundry supports compiling and deploying Solidity contracts to `Asset-Hub Westend` network on Polkadot using the `resolc` compiler.

### 1. Compilation

You can install Resolc by following the instructions [here](https://contracts.polkadot.io/revive_compiler/installation) or [here](https://github.com/paritytech/rvm-rs). If you have `resolc` available in your PATH, foundry will automatically use it.

Otherwise, you can set the path to `resolc` in your `foundry.toml` by adding the following:
```toml
[profile.default.resolc]
resolc_compile = true
resolc = "path/to/resolc"
```

`resolc` config value supports 
  - valid values follow the SemVer format `x.y.z-dev.n`, `resolc:x.y.z-dev.n`
  - path `path/to/resolc`.

### 2. Deploying

You can deploy Solidity contracts via `forge create` command:
```bash
forge create --resolc --legacy --broadcast --rpc-url $RPC_URL --private-key $PRIVATE_KEY  <path to the contract> --constructor-args '1' 
```

### 3. Solidity scripts

Currently not supported 

### 4. Limitations

- [Working forge commands](https://github.com/paritytech/foundry-polkadot/issues/54#issuecomment-2695723499)
- [Working cast commands](https://github.com/paritytech/foundry-polkadot/issues/57#issuecomment-2699458251) 
- [Known issues on `resolc` side](https://contracts.polkadot.io/known_issues/)
