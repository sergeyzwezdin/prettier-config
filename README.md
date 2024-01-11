# @sergeyzwezdin/prettier-config

Shareable prettier configuration

## Usage

1. Install package `@sergeyzwezdin/prettier-config`
```bash
npm install @sergeyzwezdin/prettier-config --save-dev
```
2. Specify prettier configuration in `package.json`
```json
{
  "name": "your-package-name",
  "prettier": "@sergeyzwezdin/prettier-config",
  "scripts": {
    "format": "prettier --write \"**/*.ts*\""
  }
}
```

## License

Released under [MIT](/LICENSE) by [Sergey Zwezdin](https://github.com/sergeyzwezdin).
