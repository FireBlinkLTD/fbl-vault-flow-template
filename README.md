# fbl-vault-flow-template

[![CircleCI](https://circleci.com/gh/FireBlinkLTD/fbl-vault-flow-template.svg?style=svg)](https://circleci.com/gh/FireBlinkLTD/fbl-vault-flow-template) [![Greenkeeper badge](https://badges.greenkeeper.io/FireBlinkLTD/fbl-vault-flow-template.svg)](https://greenkeeper.io/)

Secure storage flow template. 

Allows to setup a simple flow that allows to encrypt/decrypt files inside the "vault" folder.

## Installation

First, install [FBL](https://www.npmjs.com/package/fbl).

```bash
npm install -g fbl
```

Then generate your new plugin project with a just one command:

```bash
fbl https://github.com/FireBlinkLTD/fbl-vault-flow-template/archive/master.tar.gz
```

You can also pass all the options into command itself to avoid answering prompts:

```bash
fbl \
 -c \$.destination=/path/to/vault_folder \
 https://github.com/FireBlinkLTD/fbl-vault-flow-template/archive/master.tar.gz
```
