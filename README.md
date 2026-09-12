# tsconfig

Shared TypeScript configuration for arylo-scripts projects.

## Usage

Add the package to a project:

```json
{
  "devDependencies": {
    "@arylo-scripts/tsconfig": "github:arylo-scripts/tsconfig#v1.0.0"
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
