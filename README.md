# google-script-polyfills

Polyfills for Google Apps Scripts

## Usage

### 1. Add to your project `src` folder as Git submodule

```BASH
cd dist
git submodule add https://github.com/Glajik/gs-polyfill.git
```

### 2. Setup your .claspignore file

If you don't have it, create it in the same folder where is `.clasp.json` file.

Example of `.claspignore` file

```TEXT
# Ignore all submodule's files, except *.js in root folder
gs-polyfill/**
!gs-polyfill/*.js
```

### 3. Use it

### Update dependency

From your root of project run

```BASH
git submodule update --remote
```
