
### Instalacion y configuracion extensiones vscode
```
instalar node en la version 10.19.0
instalar las extenciones live server y live sass compiler en vscode 

    "liveSassCompile.settings.autoprefix": [
        "> 1%",
        "last 4 versions",
    ],
    "liveSassCompile.settings.formats": [
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "./src/css",
            "savePathSegmentKeys": null,
            "savePathReplaceSegmentsWith": null
        }
    ],
    "liveSassCompile.settings.excludeList": [ 
        "**/node_modules/**",
        ".vscode/**" 
    ]
    ```

  * _Ver documentacion => (uses [Browserslist](https://github.com/ritwickdey/vscode-live-sass-compiler/blob/master/docs/settings.md))._ 