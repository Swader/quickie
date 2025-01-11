
# Polygon Quickie

A very simple no-Nodejs no-react vanilla Deno project for building chain-connected applications that are statically hostable.

The initial project is a simple chain-connected coin flipper which connects your wallet to this app, then switches the chain of your wallet to whatever is defined in the `src/main.ts` file, and then flips a coin, reporting the result back to you.

## Stack

This project is built with:

- [Deno 2.0](https://deno.com/blog/v2)
- [Vanilla TS](https://www.typescriptlang.org/) via Deno
- Simple builder to bundle dist (see `build.ts`)

## How to use

1. Clone the repo
2. Modify the `src/main.ts` file to your needs, and other html files as needed
3. Run `deno run build`
4. Serve whatever ends up in the dist folder on a simple server - IPFS, S3, Arweave, Github Pages, etc.
