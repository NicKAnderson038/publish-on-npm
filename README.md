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

1. Setup an npm account (if not done aleardy)
2. Create a `package.json` at application root.

```json
{
  "name": "unique-npm-project-name",
  //_begin_with_1.0.0
  "version": "1.0.0",
  "description": "Descripton of my application",
  "main": "index.min.js",
  //_open_source_license!
  "license": "MIT",
  "keywords": ["list", "of", "searchable", "key", "words"]
}
```

3. `npm login`
4. `npm publish`

##### \*\*\* update package

1. `npm login`
2. `npm version` and the new version number ie: `1.0.1`
3. `npm publish`

##### \*\*\* am i still logged in?

1. `npm whoami`

#
