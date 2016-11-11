
# Angular2 Electron Starter (with angular cli)

```bash

# angular2 cli required
npm install -g angular-cli


# install
npm install

cd ./node_modules/robotjs
HOME=~/.electron-gyp node-gyp rebuild --target=1.4.5 --arch=x64 --dist-url=https://atom.io/download/electron
cd ../../

# run webpack dev server
npm start

# run karma tests
npm test

# build angular project
npm run build

# preview electron (without angular build)
npm run electron

# create electron package (build included)
npm run package

```
