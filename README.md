# Serverless Stripe backend

The backend for a serverless stripe application.
Built with AWS Lambda and the Serverless Framework.


## Setup

### Prerequisites

- Node.js & NPM
- Yarn
- [The Serverless Framework](https://serverless.com/framework/)

### Install dependencies

```
yarn
```

### Running Tests

```
yarn test
```

### Get Test coverage

```
yarn test:coverage
```

### Lint

```
yarn eslint
```

### Deploy

```
serverless deploy
```

## Configuration

Enter your configuration variables in `secrets.json`. Example:

```javascript
{
  "stripeSecretKey": "sk_test_123"
}
```

You need:

- Your Stripe **secret key**

## Thanks

**serverless-stripe-backend** © 2017+, Yos Riady. Released under the [MIT] License.<br>
Authored and maintained by Yos Riady with help from contributors ([list][contributors]).
