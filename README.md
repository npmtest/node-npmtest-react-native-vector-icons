# npmtest-react-native-vector-icons

#### basic test coverage for  [react-native-vector-icons (v4.0.1)](https://github.com/oblador/react-native-vector-icons)  [![npm package](https://img.shields.io/npm/v/npmtest-react-native-vector-icons.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-native-vector-icons) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-native-vector-icons.svg)](https://travis-ci.org/npmtest/node-npmtest-react-native-vector-icons)

#### Customizable Icons for React Native with support for NavBar/TabBar/ToolbarAndroid, image source and full styling.

[![NPM](https://nodei.co/npm/react-native-vector-icons.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-vector-icons)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-native-vector-icons/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-native-vector-icons/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-native-vector-icons/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-native-vector-icons/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/test-report.html](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-native-vector-icons/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-vector-icons/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-vector-icons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-vector-icons/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-native-vector-icons/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joel Arvidsson"
    },
    "bin": {
        "generate-icon": "./generate-icon.js"
    },
    "bugs": {
        "url": "https://github.com/oblador/react-native-vector-icons/issues"
    },
    "dependencies": {
        "lodash": "^4.0.0",
        "yargs": "^6.3.0"
    },
    "description": "Customizable Icons for React Native with support for NavBar/TabBar/ToolbarAndroid, image source and full styling.",
    "devDependencies": {
        "babel": "^6.5.2",
        "babel-eslint": "^7.0.0",
        "eslint": "^3.7.1",
        "eslint-config-airbnb": "^13.0.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^2.2.3",
        "eslint-plugin-react": "^6.4.1",
        "evil-icons": "^1.8.0",
        "font-awesome": "^4.6.3",
        "ionicons": "^3.0.0",
        "material-design-icons": "^3.0.1",
        "mdi": "1.7.22",
        "octicons": "^5.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "39c05d2e775deeb98d5afdbda5dcf67965ff674f",
        "tarball": "https://registry.npmjs.org/react-native-vector-icons/-/react-native-vector-icons-4.0.1.tgz"
    },
    "gitHead": "5fcf350443be137b894021057ef9f287d3d1ff9a",
    "homepage": "https://github.com/oblador/react-native-vector-icons",
    "keywords": [
        "react-native",
        "react-component",
        "react-native-component",
        "react",
        "mobile",
        "ios",
        "android",
        "osx",
        "windows",
        "macos",
        "ui",
        "icon",
        "icons",
        "vector",
        "retina",
        "font"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "oblador"
        }
    ],
    "name": "react-native-vector-icons",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/oblador/react-native-vector-icons.git"
    },
    "rnpm": {
        "assets": [
            "Fonts"
        ]
    },
    "scripts": {
        "build": "rm -rf {Fonts,Entypo.js,EvilIcons.js,FontAwesome.js,Foundation.js,Ionicons.js,MaterialIcons.js,MaterialCommunityIcons.js,Octicons.js,Zocial.js,SimpleLineIcons.js,glyphmaps} && mkdir Fonts glyphmaps && npm run build-entypo && npm run build-evilicons && npm run build-fontawesome && npm run build-foundation && npm run build-ionicons && npm run build-materialicons && npm run build-materialcommunityicons && npm run build-octicons && npm run build-zocial && npm run build-simplelineicons",
        "build-entypo": "mkdir -p tmp/svg && curl https://dl.dropboxusercontent.com/u/4339492/entypo.zip > tmp/entypo.zip && unzip -j tmp/entypo.zip *.svg -x __MACOSX/* -d tmp/svg && fontcustom compile tmp/svg -o tmp -n Entypo -t css -h && node generate-icon tmp/Entypo.css --componentName=Entypo --fontFamily=Entypo --template=templates/separated-icon-set.tpl --glyphmap=glyphmaps/Entypo.json > Entypo.js && cp tmp/Entypo.ttf Fonts && rm -rf {tmp,.fontcustom-manifest.json}",
        "build-evilicons": "fontcustom compile node_modules/evil-icons/assets/icons -o tmp -n EvilIcons -t css -h && node generate-icon tmp/EvilIcons.css --prefix=.icon-ei- --componentName=EvilIcons --template=templates/separated-icon-set.tpl --glyphmap=glyphmaps/EvilIcons.json --fontFamily=EvilIcons > EvilIcons.js && cp tmp/EvilIcons.ttf Fonts && rm -rf {tmp,.fontcustom-manifest.json}",
        "build-fontawesome": "node generate-icon node_modules/font-awesome/css/font-awesome.css --prefix=.fa- --componentName=FontAwesome --fontFamily=FontAwesome --template=templates/separated-icon-set.tpl --glyphmap=glyphmaps/FontAwesome.json > FontAwesome.js && cp node_modules/font-awesome/fonts/fontawesome-webfont.ttf Fonts/FontAwesome.ttf",
        "build-foundation": "node generate-icon bower_components/foundation-icon-fonts/foundation-icons.css --prefix=.fi- --componentName=Foundation --fontFamily=fontcustom --template=templates/separated-icon-set.tpl --glyphmap=glyphmaps/Foundation.json > Foundation.js && cp bower_components/foundation-icon-fonts/foundation-icons.ttf Fonts/Foundation.ttf",
        "build-ionicons": "node generate-icon node_modules/ionicons/dist/css/ionicons.css --prefix=.ion- --componentName=Ionicons --fontFamily=Ionicons --template=templates/separated-icon-set.tpl --glyphmap=glyphmaps/Ionicons.json > Ionicons.js && cp node_modules/ionicons/dist/fonts/ionicons.ttf Fonts/Ionicons.ttf",
        "build-materialcommunityicons": "node generate-icon node_modules/mdi/css/materialdesignicons.css --prefix=.mdi- --componentName=MaterialCommunityIcons --fontFamily='Material Design Icons' --template=templates/separated-icon-set.tpl --glyphmap=glyphmaps/MaterialCommunityIcons.json > MaterialCommunityIcons.js && cp node_modules/mdi/fonts/materialdesignicons-webfont.ttf Fonts/MaterialCommunityIcons.ttf",
        "build-materialicons": "node generate-material-icons node_modules/material-design-icons/iconfont/codepoints --componentName=MaterialIcons --fontFamily='Material Icons' --template=templates/separated-icon-set.tpl --glyphmap=glyphmaps/MaterialIcons.json > MaterialIcons.js && cp node_modules/material-design-icons/iconfont/MaterialIcons-Regular.ttf Fonts/MaterialIcons.ttf",
        "build-octicons": "fontcustom compile node_modules/octicons/build/svg -o tmp -n Octicons -t css -h && node generate-icon tmp/Octicons.css --prefix=.icon- --componentName=Octicons --template=templates/separated-icon-set.tpl --glyphmap=glyphmaps/Octicons.json --fontFamily=Octicons > Octicons.js && cp tmp/Octicons.ttf Fonts && rm -rf {tmp,.fontcustom-manifest.json}",
        "build-simplelineicons": "node generate-icon bower_components/simple-line-icons/css/simple-line-icons.css --prefix=.icon- --componentName=SimpleLineIcons --fontFamily=simple-line-icons --template=templates/separated-icon-set.tpl --glyphmap=glyphmaps/SimpleLineIcons.json > SimpleLineIcons.js && cp bower_components/simple-line-icons/fonts/Simple-Line-Icons.ttf Fonts/SimpleLineIcons.ttf",
        "build-zocial": "node generate-icon bower_components/css-social-buttons/css/zocial.css --prefix=.zocial. --componentName=Zocial --fontFamily=zocial --template=templates/separated-icon-set.tpl --glyphmap=glyphmaps/Zocial.json > Zocial.js && cp bower_components/css-social-buttons/css/zocial.ttf Fonts/Zocial.ttf",
        "test": "eslint index.js lib/{create-icon-set-from-fontello,create-icon-set-from-icomoon,create-icon-set,icon-button,tab-bar-item-ios,toolbar-android}.js"
    },
    "version": "4.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
