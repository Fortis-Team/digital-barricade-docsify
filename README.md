# Digital Barricade Documentation - Cloud App

> Cloud based software for simple content management.

## Documentation Website

[https://docs.digitalbarricade.com](https://docs.digitalbarricade.com)

## Development

### Setup

Install `docsify-cli `. Check [Docsify](https://docsify.js.org/#/quickstart) for more info.

```bash
  npm i docsify-cli -g
```

Run local server

```bash
  docsify serve
```

[http://localhost:3000](http://localhost:3000)

### Git flow

- `main` - production branch
- `dev` - base for development. Merge to main ONLY when deploying to prod.
- `{feature|fix}/{dev initial}-{task}` - branch out from `dev` then PR back to `dev` branch

## Deployment

Merge `dev` branch to `main` branch
