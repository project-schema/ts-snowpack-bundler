## Vanila Ts project init

- Create {index.html}
- init package.json

```bash
npm init --y
```

- install typescript for dev dependency

```bash
npm i --save-dev typescript
```

- ts config file

```bash
npx tsc --init
```

- change outDir and rootDir in tsconfig.json
- change module to es6 other wise you cannot add import export
<p>but it will error because browser can not understand module for solution we need bundler
</p>

## Lets add bundler for Ts

**There is lots of Bundler Like Snowpack or Webpack**

**Delete All FILES**
**Delete All FILES**

- We Are using Snowpack

```bash
npx create-snowpack-app . --template @snowpack/app-template-blank-typescript --force
```

```text
http://localhost:8080
```

```text
npm install      Install your dependencies. (We already ran this one for you!)
npm start        Start your development server.
npm run build    Build your website for production.
npm test         Run your tests.
```

- You have to care about js link will be like this

```html
<script type="module" src="/dist/index.js"></script>
```
