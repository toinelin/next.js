# Hello World example

## How to use

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/segmentio/create-next-app) with [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) or [npx](https://github.com/zkat/npx#readme) to bootstrap the example:

```bash
npx create-next-app --example using-nerv using-nerv-app
# or
yarn create next-app --example using-nerv using-nerv-app
```

### Download manually

Download the example:

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/using-nerv
cd using-nerv
```

Install it and run:

```bash
npm install
npm run dev
# or
yarn
yarn dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
now
```

## The idea behind the example

This example uses [Nerv](https://nerv.aotu.io/) instead of React. It's a "blazing fast React alternative, compatible with IE8 and React 16". Here we've customized Next.js to use Nerv instead of React.

Here's how we did it:

- Use `next.config.js` to customize our webpack config to support [Nerv](https://nerv.aotu.io/)
