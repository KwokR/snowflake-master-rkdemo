## ⚠️ Heads up: Medium isn't using this tool anymore, but you're welcome to!
[Read more about our current thinking around engineer growth](https://medium.engineering/engineering-growth-at-medium-4935b3234d25).

# Snowflake

Snowflake is Medium's tool for planning and supporting our engineers' career development. You can read more
about how we use this tool in our [growth framework documentation](https://medium.com/s/engineering-growth-framework).
Our growth tool is hosted [publicly](https://snowflake.medium.com).

![The Lannisters send their regards](https://i.imgur.com/e9DYLBr.png)

## Contributions

You are free to use, change and build on this work to make it useful for your organisation. We will happily consider
unencumbered code contributions to improve functionality, but as this is the actual tool we use within Medium, acceptance is likely to be intentional, and deliberate. Meaning, slow. As such, you may prefer to fork the codebase for your own needs. We will not accept any contributions that modify the text of the application (but, thank you in advance for pointing out any typos).

## Requirements

- **Node.js**: 18.17 or higher (tested with Node.js 24.6.0)
- **npm**: 7.0 or higher

> **Note**: This codebase was upgraded in December 2024 from 2019 dependencies to modern versions (Next.js 15, React 18, D3 v7). The original version used Yarn and Flow type checking, which have been removed in favor of npm and plain JavaScript.

## Installation

Install dependencies:

```bash
npm install
```

## Running the dev server

```bash
npm run dev
```

The application will be available at [http://localhost:3000](http://localhost:3000).

## Building for production

Build the static site:

```bash
npm run build
```

This will create an optimized production build and export static files to the `out/` directory.

## Technology Stack

- **Next.js 15.1.0** - React framework with static site generation
- **React 18.3.1** - UI library
- **D3.js 7.9.0** - Data visualization library for the Nightingale chart

## Security

This codebase is regularly updated and currently has **zero known security vulnerabilities**. Run `npm audit` to verify.

## Future work

* Load initial data from a file, to improve flexibility.
* Add restricted job title selection and validation.
* Migrate to TypeScript for better type safety.
* Add automated tests.
