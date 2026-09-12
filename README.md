## tsds

CLI wrapper for [ts-dev-stack](https://github.com/kmalakoff/ts-dev-stack).

This wrapper is not currently published on the public npm registry. Use the published `ts-dev-stack` package to run the same `tsds` command:

### Use

```bash
# Run without installing locally
npx ts-dev-stack validate
npx ts-dev-stack build
npx ts-dev-stack test:node

# Or install globally
npm install -g ts-dev-stack
tsds validate
```

See [ts-dev-stack](https://github.com/kmalakoff/ts-dev-stack) for full documentation.

Node.js and npm (including `npx`) are required. Run `validate` from a TypeScript library or application configured for ts-dev-stack; see the main guide for the required project files and commands.
