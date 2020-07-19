DO NOT USE THIS IN PRODUCTION APPLICATIONS!

This package is intended to be included in fun scavenger hunts in node applications.

You should include it like this in `package.json`

```json
{
  "name": "scavenger-hunt",
  "version": "1.0.0",
  "optionalDependencies": {
    "scavenger-hunt-hidden": "@latest"
  }
}
```

The sole purpose of this package is to provide the "hidden" flag in `index.js`.
