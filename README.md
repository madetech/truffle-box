# Truffle box with Babel and OpenZeppelin

This is a default [truffle](http://truffleframework.com/) box used as a starting point at [Made Tech](https://www.madetech.com/).

It includes:
* [OpenZeppelin](https://openzeppelin.org/)
* [Babel](https://babeljs.io/) with `env` preset (for `async` / `await` in tests)

## Usage

Install Truffle:

```
npm install -g truffle
```

Use this box as a base for your next project:

```
mkdir next-project/ && cd next-project/
truffle unbox madetech/truffle-made
```