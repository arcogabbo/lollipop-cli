### What is this
This project aims to facilitate the making of a request that follows the PagoPA S.p.A. Proof of Possession 
protocol(codename lollipop) rules. With an interactive cli and some utility methods this can be achievable.

**NOTE**: **This project it's in highly experimental state.**

### How do I use it?
You can either import the lollipop utility methods or interact with the cli command `lollipop-cli`.
The cli also supports arguments instead of a prompt-based interaction. 
For example, the following argument will skip the first prompt:

```bash
lollipop-cli --flow Sign
```

### Run the cli locally for development
With `npm link` or `yarn link` you can make the command available locally. 
Another option is to just run the script `dev-cli` included in the `package.json` with the package manager of your choice.

## TODO
- More unit tests
- Remove casting from JSON to JWK utility method when presenting custom key pair
