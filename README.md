npm init -y

npm install express
npm install --save-dev @types/express

npm install --save-dev typescript ts-node nodemon

npm install --save-dev @types/node

npx tsc --init

// tsconfig.json
{
  "compilerOptions": {
    "target": "ES6",
    "rootDir": "./src",
    "strict": true,
    "esModuleInterop": true,
    "moduleResolution": "nodenext",
    "module": "NodeNext",
    "resolveJsonModule": true,
  }
}

 // 	To run 
  "dev: "nodemon file.ts"

