# Echo

## Overview

This example demonstrates a simple echo effect, where an application sends back the data it receives.

This is a Motoko example that does not currently have a Rust variant. 


## Prerequisites
This example requires an installation of:

- [x] Install the [IC SDK](../developer-docs/setup/install/index.mdx).
- [x] Download the following project files from GitHub: https://github.com/dfinity/examples/

Begin by opening a terminal window.

### Step 1: Navigate into the folder containing the project's files and start a local instance of the Internet Computer with the command:

```
cd examples/motoko/echo
`dfx start --background
```

### Step 2: Deploy the canisters `Map` and `Test`:

```
dfx deploy
```

### Step 3: Invoke the say method:

```
dfx canister call echo say '("This is a test.")'
```


The following output will be returned: 

```
("This is a test.")
```