# cspell-dict

[![npm](https://img.shields.io/npm/v/%40itprokyle%2Fcspell-dict)](https://www.npmjs.com/package/@itprokyle/cspell-dict)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit)](https://github.com/pre-commit/pre-commit)
[![renovate](https://img.shields.io/badge/enabled-brightgreen?logo=renovatebot&logoColor=%2373afae&label=renovate)](https://developer.mend.io/github/ITProKyle/cspell-dict)

My custom [cspell](https://github.com/streetsidesoftware/cspell) dictionary.

**Table Of Contents** <!-- markdownlint-disable-line MD036 -->

<!-- mdformat-toc start --slug=gitlab --no-anchors --maxlevel=6 --minlevel=2 -->

- [Installation](#installation)
- [Usage](#usage)

<!-- mdformat-toc end -->

______________________________________________________________________

## Installation

```console
$ npm install --save-dev cspell @itprokyle/cspell-dict
added ... packages, and audited ... packages in ...ms

found ... vulnerabilities
```

______________________________________________________________________

## Usage

Once installed, add the following to your project's cspell configuration file (e.g. `cspell.json`, `.vscode/cspell.json`):

```json
{
  "import": [
    "@itprokyle/cspell-dict/cspell-ext.json"
  ]
}
```

This will add our dictionary to cspell.

______________________________________________________________________
