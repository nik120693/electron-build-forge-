# electron-build-forge-webpack-typescript
Electron App template with webpack, typescript built with electron-forge

```
cd ./electron-build-forge-/
```

install node dependencies

```
npm i
```

create a .deb to install

```
npx electron-forge make
```

install the .deb

```
sudo dpkg -i out/make/deb/x64/test-build.deb
```

Now you can open the app from Application Menu in Ubuntu OS (or Debian based alternative system)
