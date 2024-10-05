# BlockchainChecker

A Symfony APP to check the status of a blockchain

## Installation

```bash
$ composer install
```

## API Checker Crypto

To use the API checker crypto, you need to create a `.env.local` file in the root directory of the project with the following content (example [.env.local](https://raw.githubusercontent.com/yoanbernabeu/BlockchainChecker/refs/heads/main/.env.local)):

This API provider is used to check the status of a blockchain. **SENSITIVE DATA**

```dotenv
# WARNING: Don't commit this to GitHub! Contains sensitive API credentials
API_KEY=
API_URL=
```

## Test your API

You can test your API with the following command:

```bash
$ curl -H "X-Api-Key: API_KEY" API_URL
```

## Usage

```bash
$ php bin/console blockchain:check
```

## License

This project is under the MIT license.