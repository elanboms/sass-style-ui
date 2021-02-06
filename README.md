# sass-style-ui
make code of  quickly toooooo much

###  npm i -D sass sass-loader

###  npm i -D sass-resources-loader

### vue.config.js中写入一下代码
```
     module.exports = {
       css: {
         loaderOptions: {
            sass: {
                // 如果sass-laoder版本<8,这里使用data
                prependData: ` @import "./src/assets/css/style_common.scss"; `,
            },
         },
        },
   }


```
