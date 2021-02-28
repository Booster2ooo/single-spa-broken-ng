Repro for (Broken default app #341)[https://github.com/single-spa/single-spa-angular/issues/341]

```
cmd>npx create-single-spa --moduleType app-parcel
? Directory for new project .
? Which framework do you want to use? angular
? Project name (can use letters, numbers, dash or underscore) single-spa-broken-ng
? Do you want to enforce stricter type checking and stricter bundle budgets in the workspace?
  This setting helps improve maintainability and catch bugs ahead of time.
  For more information, see https://angular.io/strict Yes
? Would you like to add Angular routing? Yes
? Which stylesheet format would you like to use? SCSS   [ https://sass-lang.com/documentation/syntax#scss
 ]
CREATE single-spa-broken-ng/angular.json (3817 bytes)
CREATE single-spa-broken-ng/package.json (1210 bytes)
CREATE single-spa-broken-ng/README.md (1026 bytes)
CREATE single-spa-broken-ng/tsconfig.json (783 bytes)
CREATE single-spa-broken-ng/tslint.json (3185 bytes)
CREATE single-spa-broken-ng/.editorconfig (274 bytes)
CREATE single-spa-broken-ng/.gitignore (631 bytes)
CREATE single-spa-broken-ng/.browserslistrc (703 bytes)
CREATE single-spa-broken-ng/karma.conf.js (1437 bytes)
CREATE single-spa-broken-ng/tsconfig.app.json (287 bytes)
CREATE single-spa-broken-ng/tsconfig.spec.json (333 bytes)
CREATE single-spa-broken-ng/src/favicon.ico (948 bytes)
CREATE single-spa-broken-ng/src/index.html (303 bytes)
CREATE single-spa-broken-ng/src/main.ts (372 bytes)
CREATE single-spa-broken-ng/src/polyfills.ts (2830 bytes)
CREATE single-spa-broken-ng/src/styles.scss (80 bytes)
CREATE single-spa-broken-ng/src/test.ts (753 bytes)
CREATE single-spa-broken-ng/src/assets/.gitkeep (0 bytes)
CREATE single-spa-broken-ng/src/environments/environment.prod.ts (51 bytes)
CREATE single-spa-broken-ng/src/environments/environment.ts (662 bytes)
CREATE single-spa-broken-ng/src/app/app-routing.module.ts (245 bytes)
CREATE single-spa-broken-ng/src/app/app.module.ts (393 bytes)
CREATE single-spa-broken-ng/src/app/app.component.html (25757 bytes)
CREATE single-spa-broken-ng/src/app/app.component.spec.ts (1099 bytes)
CREATE single-spa-broken-ng/src/app/app.component.ts (225 bytes)
CREATE single-spa-broken-ng/src/app/app.component.scss (0 bytes)
CREATE single-spa-broken-ng/e2e/protractor.conf.js (904 bytes)
CREATE single-spa-broken-ng/e2e/tsconfig.json (274 bytes)
CREATE single-spa-broken-ng/e2e/src/app.e2e-spec.ts (671 bytes)
CREATE single-spa-broken-ng/e2e/src/app.po.ts (274 bytes)
√ Packages installed successfully.
warning: LF will be replaced by CRLF in .browserslistrc.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .editorconfig.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in angular.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in e2e/protractor.conf.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in e2e/src/app.e2e-spec.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in e2e/src/app.po.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in e2e/tsconfig.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in karma.conf.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in package-lock.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in package.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/app/app-routing.module.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/app/app.component.html.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/app/app.component.spec.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/app/app.component.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/app/app.module.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/environments/environment.prod.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/environments/environment.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/index.html.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/main.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/polyfills.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/styles.scss.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/test.ts.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in tsconfig.app.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in tsconfig.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in tsconfig.spec.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in tslint.json.
The file will have its original line endings in your working directory
    Successfully initialized git.
Installing packages for tooling via npm.
Installed packages for tooling via npm.
? Does your application use Angular routing? Yes
? Does your application use BrowserAnimationsModule? No
    Added 'single-spa' as a dependency
    Added 'single-spa-angular' as a dependency
    Added '@angular-builders/custom-webpack' as a dependency
    Generated 'main.single-spa.ts
    Generated 'single-spa-props.ts
    Generated asset-url.ts
    Generated extra-webpack.config.js
    Using @angular-devkit/custom-webpack builder.
    Updated angular.json configuration
    @angular-builders/custom-webpack:browser
CREATE extra-webpack.config.js (303 bytes)
CREATE src/main.single-spa.ts (932 bytes)
CREATE src/app/empty-route/empty-route.component.ts (143 bytes)
CREATE src/single-spa/asset-url.ts (502 bytes)
CREATE src/single-spa/single-spa-props.ts (333 bytes)
UPDATE package.json (1618 bytes)
UPDATE tsconfig.app.json (196 bytes)
UPDATE angular.json (4025 bytes)
For further routing setup, see https://single-spa.js.org/docs/ecosystem-angular#configure-routes
Project setup complete!
Steps to test your Angular single-spa application:
1. Run 'npm run serve:single-spa:single-spa-broken-ng'
2. Go to http://single-spa-playground.org/playground/instant-test?name=single-spa-broken-ng&url=%2F%2Flocalhost%3A4200%2Fmain.js&framework=angular to see it working!

cmd>cd single-spa-broken-ng
cmd>npm run serve:single-spa:single-spa-broken-ng

> single-spa-broken-ng@0.0.0 serve:single-spa:single-spa-broken-ng C:\Dev\Neuroglia\Cisco\portal\ui-next\single-spa-broken-ng
> ng s --project single-spa-broken-ng --disable-host-check --port 4200 --deploy-url http://localhost:4200/ --live-reload false

An unhandled exception occurred: Cannot find module '@angular-builders/custom-webpack/package.json'
See "C:\Users\Booster\AppData\Local\Temp\ng-eX4ieg\angular-errors.log" for further details.
npm ERR! code ELIFECYCLE
npm ERR! syscall spawn
npm ERR! file C:\WINDOWS\system32\cmd.exe
npm ERR! errno ENOENT
npm ERR! single-spa-broken-ng@0.0.0 serve:single-spa:single-spa-broken-ng: `ng s --project single-spa-broken-ng --disable-host-check --port 4200 --deploy-url http://localhost:4200/ --live-reload false`
npm ERR! spawn ENOENT
npm ERR!
npm ERR! Failed at the single-spa-broken-ng@0.0.0 serve:single-spa:single-spa-broken-ng script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Booster\AppData\Roaming\npm-cache\_logs\2021-02-28T10_49_55_254Z-debug.log

cmd> npm i
npm WARN @angular-devkit/build-angular@0.1101.4 requires a peer of @angular/localize@^11.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN @angular-devkit/build-angular@0.1101.4 requires a peer of ng-packagr@^11.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN ws@7.4.3 requires a peer of bufferutil@^4.0.1 but none is installed. You must install peer dependencies yourself.
npm WARN ws@7.4.3 requires a peer of utf-8-validate@^5.0.2 but none is installed. You must install peer dependencies yourself.
npm WARN ws@7.4.3 requires a peer of bufferutil@^4.0.1 but none is installed. You must install peer dependencies yourself.
npm WARN ws@7.4.3 requires a peer of utf-8-validate@^5.0.2 but none is installed. You must install peer dependencies yourself.
npm WARN sass-loader@10.1.1 requires a peer of node-sass@^4.0.0 || ^5.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN sass-loader@10.1.1 requires a peer of fibers@>= 3.1.0 but none is installed. You must install peer dependencies yourself.
npm WARN webpack-subresource-integrity@1.5.2 requires a peer of html-webpack-plugin@>= 2.21.0 < 5 but none is installed. You must install peer dependencies yourself.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@2.3.2 (node_modules\chokidar\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@2.3.2: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@2.1.3 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@2.1.3: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.13 (node_modules\watchpack-chokidar2\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.13 (node_modules\webpack-dev-server\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

added 8 packages from 13 contributors and audited 1638 packages in 9.616s
found 0 vulnerabilities

cmd>npm run serve:single-spa:single-spa-broken-ng

> single-spa-broken-ng@0.0.0 serve:single-spa:single-spa-broken-ng C:\Dev\Neuroglia\Cisco\portal\ui-next\single-spa-broken-ng
> ng s --project single-spa-broken-ng --disable-host-check --port 4200 --deploy-url http://localhost:4200/ --live-reload false

Option "deployUrl" is deprecated: Use the "deployUrl" option in the browser builder instead.
    Warning: --deploy-url and/or --base-href contain unsupported values for ng serve. Default serve path of '/' used. Use --serve-path to override.
Warning: Running a server with --disable-host-check is a security risk. See https://medium.com/webpack/webpack-dev-server-middleware-security-issues-1489d950874a for more information.
Compiling @angular/core : es2015 as esm2015
Compiling @angular/common : es2015 as esm2015
Compiling single-spa-angular/internals : es2015 as esm2015
Compiling @angular/platform-browser : es2015 as esm2015
Compiling @angular/platform-browser-dynamic : es2015 as esm2015
Compiling single-spa-angular : es2015 as esm2015
Compiling @angular/router : es2015 as esm2015
√ Browser application bundle generation complete.

Initial Chunk Files | Names         |    Size
main.js             | main          | 2.46 MB

                    | Initial Total | 2.46 MB

Build at: 2021-02-28T10:52:03.980Z - Hash: 0b59c7ae55543ad3512a - Time: 19366ms

Warning: C:\Dev\Neuroglia\Cisco\portal\ui-next\single-spa-broken-ng\node_modules\single-spa-angular\__ivy_ngcc__\fesm2015\single-spa-angular.js depends on 'single-spa-angular/internals'. CommonJS or AMD dependencies can cause optimization bailouts.
For more info see: https://angular.io/guide/build#configuring-commonjs-dependencies



** Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/ **


√ Compiled successfully.
√ Browser application bundle generation complete.

1 unchanged chunks

Build at: 2021-02-28T10:52:05.680Z - Hash: f5e8da17b1da200616e7 - Time: 1115ms

√ Compiled successfully.
```