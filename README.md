# @parsifer/prettier-config
Base prettier configuration used by the Parsifer team for packages and the applications.

## Installation

Install the package from the npm registry.

```sh
npm i -D @parsifer/prettier-config

# Make sure also to install the following packages peer dependancies
npm i -D prettier
```

## Usage

After installation, you can copy/paste the following block of code within the `package.json` file.

```json
{
  "prettier": "@parsifer/prettier-config"
}
```

Alternatively, you can add the following string to a `prettierrc.json` configuration file.
```json
    "@parsifer/prettier-config"
```
Read more about Prettier configurations on their website: https://prettier.io/docs/en/configuration.html.