# How To Publish On NPM

<br>
<br>
<br>

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Npm-logo.svg/1200px-Npm-logo.svg.png" width=200>

<br>
<br>

### We could use your help! Please share your experience & code if you got a solution 🛠️to a unique problem 🚀. The community needs your support! ❤️

### Working with npm packages

##### \*\*\* New package

1. Setup an npm account. (if not done aleardy)
2. Create a `package.json` at application root and set version `1.0.0` to start. \*\*\* If open source, set the license to `MIT`. 🤟

```json
{
  "name": "unique-npm-project-name",
  "version": "1.0.0",
  "description": "Descripton of my application",
  "main": "index.min.js",
  "license": "MIT",
  "keywords": ["list", "of", "searchable", "key", "words"]
}
```

3. Push changes to your git repo.
4. `npm login`
5. `npm publish`

##### \*\*\* update package

1. Push changes to your git repo
2. `npm login`
3. `npm version` with new number

```bash
# example
npm verison 1.0.1
```

4. `npm publish`

##### \*\*\* am i still logged in?

1. `npm whoami`

#
