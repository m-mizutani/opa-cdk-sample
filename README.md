# Example of AWS Lambda with OPA/Rego

## Prerequisite

- go >= 1.17
- aws-cdk >= 1.134.0

## How to deploy

Change stack name from `opa-test` in [bin/cdk.ts](bin/cdk.ts) if you want.

```ts
new CdkStack(app, "opa-test", {
```

Set environment variables.

- `AWS_ACCOUNT`
- `AWS_REGION`
- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`

Then, run deploy command.

```bash
$ npm i
$ cdk deploy
```

## License

MIT License
