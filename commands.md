# Commands

## To Run 

npm run start

## Clear cache

npx docusaurus clear


## Git Commands ----

Git add ---- git add .

Git commit ---- git commit -m "message"

Git push ----- git push origin [branchname]

Pull Branch ---- git pull origin [branchname]

Pull Main ---- git pull origin main

delete branch --- git branch -D [branchName]

## Issues Faced and Solution

### Issue
- Faced this issue, when i clone repository in another folder

`tsconfig.json`
    Error line shows File `@docusaurus/tsconfig` not found.
   
### Solution   
```js
npm install
or
npm install --only=dev
or
npm install --save-dev @docusaurus/tsconfig
```

- In VS Code: Press `Ctrl + Shift + P`, type `TypeScript: Restart TS server`, and press Enter.

