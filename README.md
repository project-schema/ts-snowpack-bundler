## Lets add bundler for Ts

**There is lots of Bundler Like Snowpack or Webpack**

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
