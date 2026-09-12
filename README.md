# tsconfig

Shared TypeScript configuration for arylo-scripts projects.

## Usage

Install the package:

```sh
npm install --save-dev @arylo-scripts/tsconfig
```

Or add it to `devDependencies`:

```json
{
  "devDependencies": {
    "@arylo-scripts/tsconfig": "^1.0.0"
  }
}
```

Extend the base configuration:

```json
{
  "extends": "@arylo-scripts/tsconfig/base.json"
}
```

Project-specific options such as `rootDir`, `outDir`, and `include` remain in
each consuming repository.
