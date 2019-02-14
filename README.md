# Training Management Tool

### Features:
- Using ES2016 (generators/async/await) then transpiled to ES5 cross-browser compatible code
- Development server with hot-reload for quick development loop
- Static dev-bundle for quick full-page reload
- Automatic build of optimized production package and deployment: `npm run bd`
- Unit test with simple test runner in TypeScript
- Typescript node support using ts-node
- Git hooks running linter before commit and tests before push
- Editorconfig and tslint as code linter

### Stack:
- TypeScript - v1.8.10
- React - v15.1.0
- MobX - v2.3.1 / mobx-react
- JSPM (0.17.X) / SystemJS / systemjs-hot-reloader

---

### Installation

##### 1. Clone repo
    git clone git@github.com:deneb0618/Training-Management-Tool.git

##### 2. Install all dependencies
    npm install

##### 3. Run development server and start developing
    npm start

### NPM commands
- `npm start` - run local development server with hot-reloader at localhost:8888
- `npm test` - run tests
- `npm run lint` - run code linter
- `npm run dev-bundle` - build & inject dev-bundle with all dependencies to index.html for faster page reload
- `npm run dev-unbundle` - remove injected dev-bundle
- `npm run build` - build production deployment package (minified)
- `npm run build-debug` - build debug deployment package (source maps)
- `npm run init-deploy` - init deployment repository
- `npm run deploy` - commit to deployment repository & push to remote
- `npm run bd` - automatic build and deployment

---

### Todo
- PouchDB as persistence layer for stores
- editorconfig.org setup
