# BANHANG
Ngu Cút , ĐELL Ăn cắp nghe chưa mấy thằng ngu
C:\Users\admin\Desktop\HTKApp>npm run web

> htkapp@1.0.0 web
> expo start --web

Starting project at C:\Users\admin\Desktop\HTKApp
Starting Metro Bundler
▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
█ ▄▄▄▄▄ █ ██▀▀█▀▄██ ▄▄▄▄▄ █
█ █   █ █  ▀█ ▀█ ██ █   █ █
█ █▄▄▄█ █▀  █▄▀▀▄██ █▄▄▄█ █
█▄▄▄▄▄▄▄█▄█ ▀▄█▄█▄█▄▄▄▄▄▄▄█
█ ▄██  ▄▀▀█▄█▄▀▄ ███ ▀▄▄ ▄█
█▄▀▄▄█▀▄ █ ▄█▀██ ▀▀ █▄  ▀██
█ ▄ ▄▄ ▄█▀▀▀▄▀█▄▀▄▀▄▀▀▄ ▀██
███▄▄▀ ▄█▄▄▀ ▄██▄▄▄█▄▀ ▀███
█▄▄▄█▄█▄█▀█ █▄▀▄▄ ▄▄▄ ▀ ▄▄█
█ ▄▄▄▄▄ █▀▀ █▀█▀▀ █▄█ ▀▀▀▀█
█ █   █ █▄ █▄▀▄ █▄▄ ▄▄▀   █
█ █▄▄▄█ █▀ █ ▄ ▄▄██▄▀█▀▀ ██
█▄▄▄▄▄▄▄█▄▄██▄▄█████▄▄▄▄▄▄█

› Metro waiting on exp://192.168.1.4:8081
› Scan the QR code above with Expo Go (Android) or the Camera app (iOS)

› Web is waiting on http://localhost:8081

› Using Expo Go
› Press s │ switch to development build

› Press a │ open Android
› Press w │ open web

› Press j │ open debugger
› Press r │ reload app
› Press m │ toggle menu
› shift+m │ more tools
› Press o │ open project code in your editor

› Press ? │ show all commands

Logs for your project will appear below. Press Ctrl+C to exit.
Web Bundled 5295ms index.js (206 modules)
 LOG  [web] Logs will appear in the browser console
› Opening on Android...
› Opening emulator Medium_Phone_API_36.1
› Opening exp://192.168.1.4:8081 on Medium_Phone_API_36.1
Downloading the Expo Go app [================================================================] 100% 0.0s

› Press ? │ show all commands
Android Bundled 12399ms index.js (683 modules)
 ERROR  Expected ',' or '}' after property value in JSON at position 408 (line 18 column 5)

Import stack:

 index.js
 | import "expo"


 | import "./index"

 ERROR  Expected ',' or '}' after property value in JSON at position 408 (line 18 column 5)

Import stack:

 index.js
 | import "expo"


 | import "./index"

 ERROR  [Error: InternalError Metro has encountered an error: Expected ',' or '}' after property value in JSON at position 408 (line 18 column 5): C:\Users\admin\Desktop\HTKApp\node_modules\metro\src\node-haste\Package.js (23:28)

  21 |   read() {
  22 |     if (this._content == null) {
> 23 |       this._content = JSON.parse(_fs.default.readFileSync(this.path, "utf8"));
     |                            ^
  24 |     }
  25 |     return this._content;
  26 |   }]
Unable to resolve "react-native-vector-icons/MaterialIcons" from "App.js"
  11 |   Alert
  12 | } from 'react-native';
> 13 | import Icon from 'react-native-vector-icons/MaterialIcons';
     |                   ^
  14 |
  15 | // Dữ liệu mẫu sản phẩm
  16 | const initialProducts = [

Import stack:

 App.js
 | import "react-native-vector-icons/MaterialIcons"

 index.js
 | import "./App"


 | import "./index"

Unable to resolve "react-native-vector-icons/MaterialIcons" from "App.js"
  11 |   Alert
  12 | } from 'react-native';
> 13 | import Icon from 'react-native-vector-icons/MaterialIcons';
     |                   ^
  14 |
  15 | // Dữ liệu mẫu sản phẩm
  16 | const initialProducts = [

Import stack:

 App.js
 | import "react-native-vector-icons/MaterialIcons"

 index.js
 | import "./App"


 | import "./index"

 ERROR  [Error: UnableToResolveError Unable to resolve module react-native-vector-icons/MaterialIcons from C:\Users\admin\Desktop\HTKApp\App.js: react-native-vector-icons/MaterialIcons could not be found within the project or in these directories:
  node_modules
  11 |   Alert
  12 | } from 'react-native';
> 13 | import Icon from 'react-native-vector-icons/MaterialIcons';
     |                   ^
  14 |
  15 | // Dữ liệu mẫu sản phẩm
  16 | const initialProducts = []
› Stopped server

C:\Users\admin\Desktop\HTKApp>npx expo install react-native-vector-icons
› Installing 1 other package using npm
> npm install --save react-native-vector-icons
npm error code ETARGET
npm error notarget No matching version found for react-native-thermal-receipt-printer@^1.2.0.
npm error notarget In most cases you or one of your dependencies are requesting
npm error notarget a package version that doesn't exist.
npm error A complete log of this run can be found in: C:\Users\admin\AppData\Local\npm-cache\_logs\2025-12-10T11_44_41_737Z-debug-0.log
Error: npm install --save react-native-vector-icons exited with non-zero code: 1
Error: npm install --save react-native-vector-icons exited with non-zero code: 1
    at ChildProcess.completionListener (C:\Users\admin\Desktop\HTKApp\node_modules\@expo\spawn-async\build\spawnAsync.js:42:23)
    at Object.onceWrapper (node:events:623:26)
    at ChildProcess.emit (node:events:508:28)
    at cp.emit (C:\Users\admin\Desktop\HTKApp\node_modules\cross-spawn\lib\enoent.js:34:29)
    at maybeClose (node:internal/child_process:1101:16)
    at ChildProcess._handle.onexit (node:internal/child_process:305:5)
    ...
    at spawnAsync (C:\Users\admin\Desktop\HTKApp\node_modules\@expo\spawn-async\build\spawnAsync.js:7:23)
    at NpmPackageManager.runAsync (C:\Users\admin\Desktop\HTKApp\node_modules\@expo\package-manager\build\node\BasePackageManager.js:41:42)
    at C:\Users\admin\Desktop\HTKApp\node_modules\@expo\package-manager\build\node\NpmPackageManager.js:37:20
    at C:\Users\admin\Desktop\HTKApp\node_modules\@expo\package-manager\build\utils\spawn.js:14:34
    at process.processTicksAndRejections (node:internal/process/task_queues:103:5)

C:\Users\admin\Desktop\HTKApp>npm install react-native-vector-icons
npm error code ETARGET
npm error notarget No matching version found for react-native-thermal-receipt-printer@^1.2.0.
npm error notarget In most cases you or one of your dependencies are requesting
npm error notarget a package version that doesn't exist.
npm error A complete log of this run can be found in: C:\Users\admin\AppData\Local\npm-cache\_logs\2025-12-10T11_44_59_456Z-debug-0.log

C:\Users\admin\Desktop\HTKApp>rm -rf node_modules
'rm' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\HTKApp>rd /s /q node_modules

C:\Users\admin\Desktop\HTKApp>del package-lock.json

C:\Users\admin\Desktop\HTKApp>npm install
npm warn deprecated osenv@0.1.5: This package is no longer supported.
npm warn deprecated inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
npm warn deprecated @npmcli/move-file@1.1.2: This functionality has been moved to @npmcli/fs
npm warn deprecated @babel/plugin-proposal-numeric-separator@7.18.6: This proposal has been merged to the ECMAScript standard and thus this plugin is no longer maintained. Please use @babel/plugin-transform-numeric-separator instead.
npm warn deprecated @babel/plugin-proposal-optional-catch-binding@7.18.6: This proposal has been merged to the ECMAScript standard and thus this plugin is no longer maintained. Please use @babel/plugin-transform-optional-catch-binding instead.
npm warn deprecated @babel/plugin-proposal-nullish-coalescing-operator@7.18.6: This proposal has been merged to the ECMAScript standard and thus this plugin is no longer maintained. Please use @babel/plugin-transform-nullish-coalescing-operator instead.
npm warn deprecated @babel/plugin-proposal-class-properties@7.18.6: This proposal has been merged to the ECMAScript standard and thus this plugin is no longer maintained. Please use @babel/plugin-transform-class-properties instead.
npm warn deprecated rimraf@2.6.3: Rimraf versions prior to v4 are no longer supported
npm warn deprecated @babel/plugin-proposal-optional-chaining@7.21.0: This proposal has been merged to the ECMAScript standard and thus this plugin is no longer maintained. Please use @babel/plugin-transform-optional-chaining instead.
npm warn deprecated rimraf@3.0.2: Rimraf versions prior to v4 are no longer supported
npm warn deprecated @babel/plugin-proposal-object-rest-spread@7.20.7: This proposal has been merged to the ECMAScript standard and thus this plugin is no longer maintained. Please use @babel/plugin-transform-object-rest-spread instead.
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated glob@7.1.6: Glob versions prior to v9 are no longer supported
npm warn deprecated glob@7.1.6: Glob versions prior to v9 are no longer supported
npm warn deprecated glob@7.1.6: Glob versions prior to v9 are no longer supported
npm warn deprecated @babel/plugin-proposal-async-generator-functions@7.20.7: This proposal has been merged to the ECMAScript standard and thus this plugin is no longer maintained. Please use @babel/plugin-transform-async-generator-functions instead.
npm warn deprecated @xmldom/xmldom@0.7.13: this version is no longer supported, please update to at least 0.8.*

added 936 packages, and audited 937 packages in 1m

129 packages are looking for funding
  run `npm fund` for details

6 vulnerabilities (2 low, 4 high)

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.

C:\Users\admin\Desktop\HTKApp>npx expo install @expo/vector-icons
› Installing 1 SDK 50.0.0 compatible native module using npm
> npm install

up to date, audited 937 packages in 2s

129 packages are looking for funding
  run `npm fund` for details

6 vulnerabilities (2 low, 4 high)

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.

C:\Users\admin\Desktop\HTKApp>npx expo install expo-print
› Installing 1 SDK 50.0.0 compatible native module using npm
> npm install

up to date, audited 937 packages in 2s

129 packages are looking for funding
  run `npm fund` for details

6 vulnerabilities (2 low, 4 high)

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.

C:\Users\admin\Desktop\HTKApp
