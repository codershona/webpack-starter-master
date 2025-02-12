**Note: This project is deprecated.** It was never a very good starter for real projects since you don't want your CSS framework to dictate your starter webpack setup — better to use vue-cli, create-react-app, etc.

We recommend using the [tailwindcss/playground](https://github.com/tailwindcss/playground) starter if you just want a simple project for playing around with Tailwind and PostCSS.

---

# Tailwind CSS Webpack Starter Project

This is an example of a super simple Webpack setup for using [Tailwind CSS](https://tailwindcss.com).

To get started, clone the project and install the dependencies:

```
# Using npm
npm install

# Using Yarn
-  yarn ;
- yarn add -D tailwindcss@next ;
- yarn upgarde ;
- run yarn dev and visit in localhost: 8080 ;
- 
```

After that, start up Webpack Development Server:

```
npm run dev
```

Webpack Development Server will watch `/src/styles.css` and `/tailwind.js` and rebuild your stylesheet on every change.

You can play around with `/index.html` to see the effects of your changes.

To build a production bundle run:

```
npm run prod
```

After that you will have a ready to deploy bundle at `/dist`

## Contributing

Have a lot of experience with Webpack and suggestions on how we could improve this starter template? We'd love a PR!
