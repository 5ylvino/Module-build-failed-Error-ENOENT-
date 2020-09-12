# Module-build-failed-Error-ENOENT-
 ERROR  Failed to compile with 1 errors

#cli
$ npm run serve

> admin@0.1.0 serve C:\projects\admin
> vue-cli-service serve

 INFO  Starting development server...
98% after emitting CopyPlugin

 ERROR  Failed to compile with 1 errors                                                4:56:01 PM

 error  in ./node_modules/core-js/modules/es.regexp.exec.js

Module parse failed: Unexpected character '�' (1:2)
You may need an appropriate loader to handle this file type, currently no loaders are configured to process this file. See https://webpack.js.org/concepts#loaders
(Source code omitted for this binary file)

 @ ./node_modules/vuetify/lib/components/VGrid/VCol.js 9:0-40
 @ ./node_modules/vuetify/lib/components/VGrid/index.js
 @ ./src/App.vue
 @ ./src/main.js
 @ multi (webpack)-dev-server/client?http://192.168.43.18:8081&sockPath=/sockjs-node (webpack)/hot/dev-server.js ./src/main.js

98% after emitting CopyPlugin

 ERROR  Failed to compile with 1 errors                                                5:02:24 PM

 error  in ./node_modules/core-js/modules/es.regexp.exec.js

Module build failed: Error: ENOENT: no such file or directory, open 'C:\projects\admin\node_modules\core-js\modules\es.regexp.exec.js'

 @ ./node_modules/vuetify/lib/components/VGrid/VCol.js 9:0-40
 @ ./node_modules/vuetify/lib/components/VGrid/index.js
 @ ./src/App.vue
 @ ./src/main.js
 @ multi (webpack)-dev-server/client?http://192.168.43.18:8081&sockPath=/sockjs-node (webpack)/hot/dev-server.js ./src/main.js
