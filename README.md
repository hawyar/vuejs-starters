# Vue.js Starter

> A collection of Vue.js starters configured with sane defaults

## Quick Overview
Each starter is stored within its own branch and new starters are given a new branch. Starters have the `with-` prefix followed by the starter name. For example `with-typescript`, `with-amplify`, `with-vuex`, `with-<your-custom-starter>`. Check out all the available [starters](https://github.com/hawyar/vuejs-starters/branches/active)

## Usage

### Using `degit` (**recommended**)
Clone from the latest commit using [degit](https://github.com/Rich-Harris/degit)
```bash
npx degit github:hawyar/vuejs-starter#starter-name my-cool-project
```
**Example using Typescript Starter**: `npx degit hawyar/vuejs-starter#with-typescript my-vue-app`

### Using `git clone`
Shallow clone with `git
```bash
git clone --branch <starter-name>https://github.com/hawyar/vuejs-starter
```
### [Why use degit over git clone?](https://github.com/Rich-Harris/degit#wait-isnt-this-just-git-clone---depth-1)
## Contributing

1. Fork it (<https://github.com/hawyar/vuejs-starter.git>)
2. Create your feature branch (`git checkout -b with-<starter-name>`)
3. Commit your changes (`git commit -am 'Add new starter <starter-name>'`)
4. Push to the branch (`git push origin with-<starter-name>`)
5. Create a new Pull Request
