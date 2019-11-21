## 1. Learn Svelte

[Svelte](https://svelte.dev/) is a radical new approach to building user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app.

Get started:
```
npx degit sveltejs/template svelte-app
mv svelte-app my-cool-app
cd my-cool-app
npm install
npm run dev
```

Open the browser in localhost:5000 and update src/App.svelte

### Resources
* Tutorial: https://svelte.dev/tutorial
* Chat: https://svelte.dev/chat
* Presentation: https://docs.google.com/presentation/d/1lqR6sJlOoGTBXpugYKph5drU8YjrlQDfzd5Dh2xzGcQ/edit#slide=id.p4

## 2. Learn Sapper

[Sapper](https://sapper.svelte.dev) is a framework for building extremely high-performance web apps. Each page of your app is a component.

Get started:
```
npx degit "sveltejs/sapper-template#rollup" my-app
cd my-app
npm install
npm run dev
```
Open the browser in localhost:3000 and update src/routes/index.svelte

## 3. Learn Sapper with tailwind

[tailwindcss](https://tailwindcss.com) is a highly customizable, low-level CSS framework.

Get started:
```
npx degit langbamit/sapper-postcss-tailwind-rollup my-app
cd my-app
npm install
npm run dev
```

Open the browser in localhost:3000 and update src/routes/index.svelte
