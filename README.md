### Step1: 
npm init -y 
### Step2: 
npm i ts-node ts-node-dev @types/node typescript --save-dev
### Step3: npx tsc --init
npx tsc --init
### Step4:
Create Folder name src and file in folder index.ts
### Step5:
Open file package.json change "main": "index.js" to "main": "index.ts" add an attribute name dev in attribute name script 
       "dev": "ts-node-dev --respawn --transpile-only src/index.ts"
### Step6:
Type code anything on file index.ts
### Step7:
Open terminal and type npm run dev to start project
