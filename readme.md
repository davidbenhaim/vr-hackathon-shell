# workbench


## Dev

```
$ npm install electron -g
$ npm install
```

## Installing [OpenCV](http://opencv.org/) && [Aruco](http://www.uco.es/investiga/grupos/ava/node/26)

```
brew tap homebrew/science
brew install opencv
```

```
wget http://downloads.sourceforge.net/project/aruco/2.0.12/aruco-2.0.12.zip
mkdir -p aruco-2.0.12
unzip aruco-2.0.12.zip -d aruco-2.0.12
cd aruco-2.0.12
mkdir build
cd build
cmake ..
make
make install
```

### Run

```
$ npm start
```

### Build

```
$ npm run build
```

Builds the app for macOS, Linux, and Windows, using [electron-packager](https://github.com/electron-userland/electron-packager).


## License

MIT © [David Benhaim](http://davidbenhaim.com)
