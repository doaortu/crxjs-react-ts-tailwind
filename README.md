## Description

This is template repository for easy scaffolding chrome extension project with crxjs with React Typescript and TailwindCSS.

### How to use

#### creating the repo
- Using web UI:
Just click the 'Use this template' button and choose between creating new repo or opening in codespace.

- Using Github CLI:
Enter this command in your terminal:
`gh repo create <your_username>/<your_new_repo_name> -p doaortu/crxjs-react-ts-tailwind`

#### install dependencies

I scaffold this project using `pnpm`, but you can also use `npm` or `yarn`.
`cd` to your newly created folder/repo and enter this command:
`pnpm i` if you want to use pnpm, `npm install` if you want to use npm, or `yarn install` if you want to use yarn.

#### run and install the extension

- run `npm run dev`, `pnpm run dev` or `yarn dev` depending on what package manager you use.
- Go to chrome extensions page `chrome://extensions`
- enable Developer mode
- click `Load unpacked` button
- navigate to your repository and choose the dist folder


