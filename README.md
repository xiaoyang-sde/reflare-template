![Header](https://raw.githubusercontent.com/booster-labs/rocket-booster/master/.github/img/header.jpg)

:rocket: The template to kickstart rocket-booster workers. The `src/index.js` file contains the code and configuration of the template. Documentation and examples for `rocket-booster` can be found [here](https://github.com/booster-labs/rocket-booster).

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/booster-labs/rocket-booster-template)

## Build and Deploy

- [Install Wrangler CLI](https://github.com/cloudflare/wrangler#installation)

```sh
npm install -g @cloudflare/wrangler
```

- Generate from [rocket-booster-template](https://github.com/booster-labs/rocket-booster-template)

```sh
wrangler generate booster https://github.com/booster-labs/rocket-booster-template
```

- Install dependencies

```sh
cd booster
npm install
```

- Authenticate Wrangler with a Cloudflare API Token

```sh
wrangler login
wrangler config
```

- Edit the configuration object in `src/index.js`

- Build and publish to Cloudflare Workers

```sh
wrangler build
wrangler publish
```
