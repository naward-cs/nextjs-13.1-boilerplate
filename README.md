# Next.js 13.1 Boilerplate

- Easy to use front-end boilerplate to start developing your Next.js application right away 💯 using the latest nextjs 13.1 app dir
- Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
- You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.
- The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.
- This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).
[**Learn More**](#learn-more)

---

## Highlights

- Features all the benefits of Next.js 13.1 app Dir
- Automatically formats your code by using `Prettier`
- Friendly errors & warnings

## File Tree

```bash
├── app                   # New nextjs App Directory 
│   └── head.tsx            # Root Header
│   └── layout.tsx          # Root Layout page
│   └── page.tsx            # Replaces the index.tsx for URI
│   └── <uri>               # URI
│       └── head.tsx          # URI Header used to modify/upate Root Header (optional)
│       └── layout.tsx        # nested layout (optional)
│       └── page.tsx          # Replaces the index.tsx for URI
├── pages                 # Pages folder can be used concurrently with App Directory
│   └── api                 # api Folder
│   └── _app.tsx            # Main page file
│   └── _document.tsx       # Custom document
│   └── index.tsx           # Home page (if App Dir has a root tsx, this cannot exist otherwise there is a conflict)
│   └── <page>.tsx          # <page> represents the page URI for each site page
├── public                # Folder for static assets
│   ├── favicon           # Favicon - https://realfavicongenerator.net/
├── src                   # Source folder to keep code organized
│   └── components          # Component folder
│   └── lib                 # Library folder
│   └── styles              # Style folder
│   └── types               # Types folder
├── .editorconfig         # IDE editor config so not one IDE is forced to be used just the format
├── .eslintrc.json        # Eslint config
├── .priettierc           # Prettier config
├──  next-env.d.ts        # Next.js Typescript declaration file (leave unchanged)
└──  tsconfig.json        # Typescript config
```

## Usage

Install dependencies

```bash
yarn install
```

Start local webserver at port 3000

```bash
yarn dev
```

Build app for production (gets output in the 'dist' directory)

```bash
yarn build
```

## Learn More

To learn more about Next.js and the other tools, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
- [Typescript](https://www.typescriptlang.org/docs/) - Introduction to TypeScript
- [Eslint](https://eslint.org/docs/user-guide) - Find and fix problems in your JavaScript code.
- [Prettier](https://prettier.io/docs/en/index.html) - Prettier is an opinionated code formatter.

## Deploy

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/project?template=)

## License

MIT
