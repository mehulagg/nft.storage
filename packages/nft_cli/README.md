<h1 align="center">⁂<br/>nft.storage</h1>
<p align="center">The CLI for nft.storage</p>

## Getting started

Install the CLI from npm

```console
$ npm install -g @wmehulagg/nft_cli
```

Login in and create a token on https://nft.storage and pass it to `nft token` to save it.

```console
$ nft token
? Paste your API token for api.nft.storage › <your token here>

⁂ API token saved
```

## Commands

### `nft put-car <path>`

Upload a [CAR](https://ipld.io/specs/transport/car/carv1/) file to nft.storage.

- `--no-retry` Don't try the upload again if it fails

<!-- ### `nft get <cid>`

Fetch files by CID. They are verified on your machine to ensure you got the eact bytes for the given CID.

- `-o, --output` The path to write the files to

### `nft list`

List all the uploads in your account.

- `--json` Format as newline delimted JSON
- `--cid` Only print the root CID per upload

### `nft status <cid>`

Get the Filecoin deals and IPFS pins that contain a given CID, as JSON. -->

### `nft token`

Paste in a token to save a new one. Pass in `--delete` to remove a previously saved token.

- `--api` URL for the Web3 Storage API. Default: https://api.nft.storage
- `--delete` Delete a previously saved token
