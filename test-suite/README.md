# Test Suite

This Test Suite uses the examples from this repo and some configuration settings, to prove interoperability between HTTP APIs for Resolution, Issuance and Verification, and Custom Credential Formats.

# Plugfest 2020 Test Suite has moved [here](https://github.com/w3c-ccg/vc-examples/tree/master/plugfest-2020)

## Getting Started

```
npm i
npm run test
```

### Adding a Resolver

Add a URL to [resolvers.json](./__fixtures__/resolvers/resolvers.json).

### Adding an Issuer

Add a URL to [issuers.json](./__fixtures__/issuers/issuers.json).

### Adding a Verifier

Add a URL to [verifiers.json](./__fixtures__/verifiers/verifiers.json).

### Adding a Credential

Add a require statement to [credentials](./__fixtures__/credentials/index.js).

### Adding a Verification

Add a require statement to [verifiable-credentials](./__fixtures__/verifiable-credentials/index.js).

## Disclaimer

These tests, APIs and credential formats are subject to change.

Expect the changes to be breaking / frustrating.
