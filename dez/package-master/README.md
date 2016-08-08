# Package

## What is this
A simple template for package.json files
This covers what I personally need when including a package.json with my projects.

*Note:* the devDependencies field can be automatically generated when
installing dependencies by using the --save-dev flag

```javascript
npm install --save-dev module-name
```

### What you get
```javascript
{
  "name": "",
  "version": "0.0.1",
  "homepage": "",
  "description": "",
  "keywords": [
    "",
    "",
    "",
    "",
    "",
    "",
    "",
    "",
    ""
  ],
  "repository": {
    "type": "git",
    "url": "http://github.com/user/repo.git"
  },
  "bugs": {
    "url": "https://github.com/user/repo/issues"
  }
  "author": {
    "name": "",
    "email": "",
    "url": ""
  },
  "contributors": [
    { "name": "", "email": "" },
    { "name": "", "email": "" }
  ],
  "engines": {
    "node": ""
  },
  "license": "MIT"
}
```

## Legend
| FIELD | VALUE |
| ----- | ----- |
| name  | name of project |
| version | semvar version of your module. *Note:* MUST be valid semvar |
| homepage | project homepage |
| description | short prose description of what your module does |
| keywords | list of keywords, this is used by npm search |
| repository | the type and location of where your source code is hosted |
| bugs | where can users file and track bugs |
| author | should be limited to one person. Email and url are optional |
| contributors | a list of all the people who helped! Acknowledgement is important |
| engines | versions of node the module is known to work on |
| license | which version of the license you are distributing your module under |
