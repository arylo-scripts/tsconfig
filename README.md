# tsconfig

Shared TypeScript configuration for arylo-scripts projects.

## Usage

Add the package to a project:

```json
{
  "devDependencies": {
    "@arylo-scripts/tsconfig": "github:arylo-scripts/tsconfig#master"
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

## Publishing

Publishing is triggered by a GitHub Release. The workflow publishes the package
to GitHub Packages using the repository `GITHUB_TOKEN`.
