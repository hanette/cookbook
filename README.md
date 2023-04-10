This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## First Time Here?
Clone the repo into a directory in your local computer:

```
git clone [URL]
```

Install npm
[Install Node.js](https://nodejs.org/en): We are using version 18.15.0 LTS
```
$ node --version
v18.15.0
```

Check that npm is installed:
```
$ npm --version
9.5.0
```

Install Next:
```
npm install next
```
Now you can run the development server and edit the website.

## Git Commands

Check status of your branch:
```
git status
```

Update your main branch:
```
git checkout main
git pull
```


Make a new branch and switch to it:
```
git checkout -b [name of new branch]
```

Before you add your files in, you want to see what changes you made:
```
git diff
```

Add the files with your new changes into a commit:
```
git add [files you want to add into the remote repo]
```

Double check your changes:
```
git diff --cached
```

Make a commit:
```
git commit
```
Which will open a text file so you can add a description of what changes you are making.


Once the commit is done, you push it into your branch:
```
git push origin [branch name that you are on]
```

Make a PR and allow others to review your branch.
Once approved and merged, delete the branch.
Delete your branch that has been merged:
```
git branch -D [branch]
```