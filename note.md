1. npm init -y
2. npm i -D typescript
3. npm i -D ts-node
4. npm i -D nodemon
5. Tạo file tsconfig.json
   {
   "compilerOptions": {
   "module": "NodeNext",
   "moduleResolution": "node",
   "baseUrl": "src",
   "outDir": "dist",
   "sourceMap": true,
   "noImplicitAny": true
   },
   "include": ["src/**/*"]
   }
6. Tạo file nodemon.json
   {
   "watch": ["src"],
   "ext": ".ts,.js",
   "exec": "ts-node ./src/index.ts"
   }
7. Tạo folder src --> tạo file index.ts
8. Vào package.json --> script
   "start": "nodemon",
9. npm i express body-parser cookie-parser compression cors
10. npm i -D @types/express @types/body-parser @types/cookie-parser @types/compression @types/cors
11. Setup file index.ts + Tạo database trên mongooseAtlas
12. npm i mongoose
13. npm i -D @types/mongoose
14. Tạo folder db
15. Tạo folder helpers --> tạo file index.ts
16. Setup file index.ts
17. Tạo folder controllers
18. Tạo folder router --> tạo file index.ts
19. Tạo folder middlewares --> tạo file index.ts
20. npm i lodash + npm i -D @types/lodash
