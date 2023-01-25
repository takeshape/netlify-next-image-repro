## Vercel

Image loads: https://netlify-next-image-repro.vercel.app/

## Netlify

Image does not load: https://precious-beijinho-b723ec.netlify.app/

## Steps to create this project

1. Create project
```
$ npx create-next-app@latest nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/learn-starter"
```
2. Edit [pages/index.js](./pages/index.js) to add a large image using `next/image`.
3. Add a simple [next.config.mjs](./next.config.mjs) file to configure `next/image` with a couple other common settings.
4. Configure Vercel deploy, totally basic, no settings or env variables touched.
5. Configure Netlify deploy, totally basic, no settings or env variables touched.
